# Setup `git` to Use SSH to Authenticate

## Create an SSH Key

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

+ The default location where the keys will be saved is `~/.ssh/`.
+ The default file names are: `id_ed25519` and `id_ed25519.pub`.

## Add Pulbic Key to Github

Open github and add the contents of `id_ed25519.pub` as a new ssh key.

## Using with git

+ To make git use ssh, use the ssh url instead of the http url.

---
