# oh-my-zsh on openwrt

[查看中文说明](./zh-cn.md)

Install oh-my-zsh on a openwrt router without git and git-http installed. It's base on the official scripts.

Package git and git-http are so large for a cheap router with a little storage.

## dependence packages

* wget
* unzip
* zsh
* ca-certificates

## Install

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/felix-fly/openwrt-ohmyzsh/master/install.sh)"
```

## Uninstall

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/felix-fly/openwrt-ohmyzsh/master/uninstall.sh)"
```
