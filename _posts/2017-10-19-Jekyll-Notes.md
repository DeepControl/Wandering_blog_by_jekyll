---
layout: post
title: 用Jekyll+Github搭建博客的学习笔记
date: 2017-10-19 08:35:55 +08:00
categories: Jekyll
---

1.
```
王国维说人生三种境界：
其一，昨夜西风凋碧树，独上高楼，望尽天涯路。
其二，衣带渐宽终不悔，为伊消得人憔悴。
其三，众里寻他千百度，蓦然回首，那人却在灯火阑珊处。
喜欢写东西的人可能也有三境界：
第一，在新浪博客，简书，微信公众号这种大的平台上写；
第二，搭建自己的博客，买主机也好，GithubPages也罢，折腾可能是一种病；
第三，我还没领悟到......
```
2.
```
Windows10 + Jekyll + GithubPages + [Domain]
```
3.
```
注册Github账户并建立自己的第一个Repositories
```
4.
```
可选：可以不需要Domain，因为能用username.github.io访问自己的主页
```
5.
```
安装Ruby，过程简单
下载地址 http://rubyinstaller.org/downloads/
安装到指定目录，例如D:\Ruby
勾选 Add Ruby executables to your PATH
```
6.
```
下载Ruby DevKit
下载地址 http://rubyinstaller.org/downloads/
解压到，例如D:\RubyDevKit
打开cmd，执行以下两条
cd D:\RubyDevKit
（进入RubyDevKit目录）
ruby dk.rb init
（准备config.yml文件）
在config.yml最后面添加
- D:\Ruby
ruby dk.rb install
```
7.DevKit在Ruby 2.4之后被MSYS2替代
```
Meet MSYS and the DevKit
Sometimes you just want RubyGems to build that cool native, C-based extension without squawking. Who’s your buddy? The DevKit that’s who!

MSYS2-DevKit (only Ruby >= 2.4)
Stating with RubyInstaller-2.4 we’re no longer using our own DevKit compilation, but make use of MSYS2 for both, building ruby itself, as well as building Ruby gems with C-extensions. It can be installed per ridk install command, which is part of RubyInstaller-2.4. Alternatively a manual download and installation from MSYS2 is also possible.

Dedicated DevKit (only Ruby < 2.4)
The RubyInstaller Development Kit is a toolkit that makes it easy to build and use native C/C++ extensions such as RDiscount and Nokogiri for Ruby on Windows. It is built upon MSYS1, which is no longer maintained, now. So you should upgrade to RubyInstaller-2.4 with makes use of MSYS2.

Simply download, double-click, choose an installation directory, run the Ruby install helper script and you’re ready to start using native Ruby extensions. For installation details check out the Development Kit wiki page.
```
8.
```
gem install jekyll
```
9.
```
安装Python和Pip
```
10.
```
pip install Pygments
```
11.
```

```
