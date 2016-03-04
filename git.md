# Check if there are uncommited files

```
git diff --quiet --exit-code
```

# Check if commit exists

```
git cat-file -e <commit>^{commit}
```

# Check if branch exists

```
git show-ref --verify --quiet refs/heads/<branch>
```

# Get current branch

```
git rev-parse --abbrev-ref HEAD
```