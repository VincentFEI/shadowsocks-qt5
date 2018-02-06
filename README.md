Shadowsocks-Qt5
===============

[![Build Status](https://travis-ci.org/shadowsocks/shadowsocks-qt5.svg?branch=master)](https://travis-ci.org/shadowsocks/shadowsocks-qt5)

Please check [project's wiki](https://github.com/shadowsocks/shadowsocks-qt5/wiki) for "how-tos".

Introduction
------------

Shadowsocks-Qt5 is a native and cross-platform [shadowsocks](http://shadowsocks.org) GUI client with advanced features.

Features
--------

- Shadowsocks-Qt5 is written in C++ with Qt 5.
- Support traffic statistics
- Support server latency (lag) test
- Use multiple profiles simultaneously
- `config.ini` is located under `~/.config/shadowsocks-qt5/` on \*nix platforms, or under the application's directory on Windows.

LICENSE
-------

![](http://www.gnu.org/graphics/lgplv3-147x51.png)

Copyright © 2014-2017 Symeon Huang

This project is licensed under version 3 of the GNU Lesser General Public License.

## 用法
- 到release界面下载Appimage格式的ShawdowSocks软件：Shadowsocks-Qt5-3.0.0-x86_64.AppImage
- 打开终端，输入： sudo chmod +x Shadowsocks-Qt5-3.0.0-x86_64.AppImage
- 运行： ./Shadowsocks-Qt5-3.0.0-x86_64.AppImage
- 随后出现和win版的gui界面一样的界面，输入自己的配置，点击Save，配置完成
- 进入ubuntu的设置，网络，网络代理，方法选择手动，在socks主机后边填上127.0.0.1，后边填写端口（默认1080），点击应用到整个系统即可开启全局代理
