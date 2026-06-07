# peeramid-labs apt repo

Public APT repository for the `slop` CLI.

```bash
curl -fsSL https://apt.peeramid.xyz/KEY.gpg | sudo apt-key add -
echo "deb https://apt.peeramid.xyz stable main" | sudo tee /etc/apt/sources.list.d/peeramid.list
sudo apt update
sudo apt install slop
```

Maintained by [Peeramid Labs](https://peeramid.xyz/). MIT-licensed
binary in this repo: [`slop-cli`](https://github.com/peeramid-labs/slop-cli).
