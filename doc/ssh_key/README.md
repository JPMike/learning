[*Back to Index*](https://github.com/jpmike/learning#index)

# ssh key

- [how to check for existing ssh keys](#how-to-check-for-existing-ssh-keys)
- [how to generate ssh keys](#how-to-generate-ssh-keys)
- [Reference](#reference)

[*top ↑*](#ssh-key)
<br><hr>

## how to check for existing ssh keys

```sh
ls -al ~/.ssh
```

check public SSH key file like:

- id_rsa.pub
- id_ecdsa.pub
- id_ed25519.pub

[*top ↑*](#ssh-key)
<br><br>

## how to generate ssh keys

```sh
ssh-keygen -t ed25519 -C "your_email@example.com"
```

for legacy system that doesn't supoort ed25519 algorithm

```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

[*top ↑*](#ssh-key)
<br><br>

## Reference

- [Connecting to GitHub with SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

[*top ↑*](#ssh-key)
<br><br>
