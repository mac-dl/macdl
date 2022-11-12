---
title: Parallels Desktop
date: 2022-11-12 10:59:18
description: Parallels Desktop for Mac 在 Mac 上运行 Windows 一款运行快速、操作简单、功能强大的应用程序，无需重启即可在您的 Intel 或 Apple M 系列 Mac 上运行 Windows。
---


## 安装
1. 下载并安装 [https://download.parallels.com/desktop/v18/18.1.0-53311/ParallelsDesktop-18.1.0-53311.dmg](https://download.parallels.com/desktop/v18/18.1.0-53311/ParallelsDesktop-18.1.0-53311.dmg)
2. 退出帐号
3. 下载并解压 [ParallelsDesktopCrack.zip](https://465.lanzout.com/i5jjo0frfvfe)
4. 给终端程序赋予磁盘文件的所有访问权限
5. 使用第 4 步的终端进入解压目录执行 `chmod +x ./install.sh && sudo ./install.sh`

## 屏蔽更新 Hosts
```text
127.0.0.1 download.parallels.com
127.0.0.1 update.parallels.com
127.0.0.1 desktop.parallels.com
127.0.0.1 download.parallels.com.cdn.cloudflare.net
127.0.0.1 update.parallels.com.cdn.cloudflare.net
127.0.0.1 desktop.parallels.com.cdn.cloudflare.net
127.0.0.1 www.parallels.cn
127.0.0.1 www.parallels.com
127.0.0.1 www.parallels.de
127.0.0.1 www.parallels.es
127.0.0.1 www.parallels.fr
127.0.0.1 www.parallels.nl
127.0.0.1 www.parallels.pt
127.0.0.1 www.parallels.ru
127.0.0.1 www.parallelskorea.com
127.0.0.1 reportus.parallels.com
127.0.0.1 parallels.cn
127.0.0.1 parallels.com
127.0.0.1 parallels.de
127.0.0.1 parallels.es
127.0.0.1 parallels.fr
127.0.0.1 parallels.nl
127.0.0.1 parallels.pt
127.0.0.1 parallels.ru
127.0.0.1 parallelskorea.com
127.0.0.1 pax-manager.myparallels.com
127.0.0.1 myparallels.com
127.0.0.1 my.parallels.com
```

锁住 hosts
```shell
sudo chflags uchg /etc/hosts
sudo chflags schg /etc/hosts
```

## 手动安装系统
- Apple Silicon
    - https://update.parallels.com/desktop/v18/appliances_arm.xml
    - https://update.parallels.com/desktop/v18/appliances_arm_Monterey.xml
- Intel
    - https://update.parallels.com/desktop/v18/appliances.xml

## 来源
[ParallelsDesktopCrack](https://notabug.org/somebasj/ParallelsDesktopCrack)
