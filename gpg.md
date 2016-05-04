#GPG

## Import keys

    gpg --allow-secret-key-import --import private.key
    gpg --import public.key
  
## Sign a file

    gpg --sign file

## Verify a signature

    gpg --verify file
  
## Extract a signed file

    gpg --output file --decrypt file.gpg
