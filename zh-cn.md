# 在 openwrt 中安装 oh-my-zsh

oh-my-zsh 官方的安装脚本需要预先安装 git 和 git-http，但是这两个包对于小内存的路由器来说实在是太大了。此处的脚本是基于官方脚本改造的，不使用git而是通过wget获取源码的zip包的方式来安装。

## 依赖的包

* wget
* unzip
* zsh
* ca-certificates

## 安装

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/felix-fly/openwrt-ohmyzsh/master/install.sh)"
```

## 卸载

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/felix-fly/openwrt-ohmyzsh/master/uninstall.sh)"
```