# ScrapeFun Desktop for Windows

这个仓库只用于发布 ScrapeFun Windows 桌面版安装包。

这里不存放 ScrapeFun 的源代码，也不作为开发仓库使用。请从本仓库的
[Releases](https://github.com/HaoweiLi97/scrapefun-desktop-windows/releases)
页面下载安装包。

## 下载

在 Releases 页面下载最新的：

```text
ScrapeFun-setup.exe
```

下载后双击安装即可。

## Windows 桌面版说明

- 安装后会在系统托盘运行 ScrapeFun 服务。
- 双击右下角托盘图标会用默认浏览器打开 ScrapeFun 网页端。
- 不内嵌桌面 WebView，不需要单独打开桌面 client。
- 支持开机启动、局域网访问、查看数据目录和日志目录。

## 数据位置

运行数据默认保存在：

```text
%APPDATA%\ScrapeFunDesktop
```

卸载程序不会自动删除用户数据。如需完全清空，请手动删除上面的目录。

## Release 仓库用途

这个仓库仅用于：

- 发布 Windows 安装包
- 维护安装包下载说明
- 记录面向用户的版本发布信息

不用于：

- 存放源代码
- 提交 issue 级别的开发讨论
- 作为构建源码仓库
