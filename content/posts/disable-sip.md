---
title: macOS SIP
date: 2022-10-23 13:56:59
description: SIP 全称为「System Integrity Protection」, 中文名「系统完整性保护」，是macos系统的一项安全技术，SIP 将一些文件目录和系统应用保护了起来。但这会影响我们一些使用或设置，比如：更改系统应用图标、终端操作系统目录文件提示「Operation not permitted」、Finder 无法编辑系统目录里的文件。
hidden: true
---

## 禁用 macOS SIP

### 1. 在 macOS 恢复模式下启动 Mac。
- 英特尔：重新启动计算机。屏幕变黑后，按住 Cmd + R 键，直到屏幕上出现 Apple 图标。启动完成后，您将进入恢复模式。

- 苹果芯片：按住 Mac 上的电源按钮（10 秒钟）。然后转到“选项”。您可能需要管理员密码。

### 2. 从 “实用工具” 菜单中启动 “终端”
<img src="https://tiku.huatu.com/cdn/pandora/img/c6c7c383-2a6e-46b0-948d-862a0f5c2612.png" referrerpolicy="no-referrer" alt="terminal.png" height="200px"/>

### 3. 执行关闭命令
```shell
csrutil disable
```
<img src="https://tiku.huatu.com/cdn/pandora/img/43cbb7da-f737-4266-ac9e-9dd5af8c86cb.png" referrerpolicy="no-referrer" alt="csrutil.png" height="200px"/>

显示 `Successfully disabled System Integrity Protection.Please restart the machine for the changes to take effect.` 就是关闭成功了，然后重启计算机。

## 恢复 macOS SIP
在 [3. 执行关闭命令](#3-执行关闭命令) 处执行 `csrutil enable` 即可。