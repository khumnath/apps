A PPA repository for debian based  linux packages:

- [joincap](https://github.com/khumnath/apps)


# Usage

```bash
curl -SsL https://khumnath.github.io/apps/repo/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/various.list https://khumnath.github.io/apps/repo/various.list
sudo apt update
sudo apt install  app-name
```