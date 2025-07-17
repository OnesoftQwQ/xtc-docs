---
sidebar_position: 1
---

# 1. 准备必要工具

要手动破解手表，你需要准备以下工具：

 - ADB：用于操控手表
 - QFIL：用于读写分区
 - Fastboot：用于写入 Userdata
 - MagiskBoot：用于修补 BOOT 镜像

你可以 [在这里](https://share.onesoft.top/s/5127bf15bb0b4d0196) 下载所需的工具。

:::tip
QFIL 工具对应下载链接中的 `QPST刷机工具`，Fastboot 工具则包含在 `ADB工具包` 中
:::

如果你的手表是低版本，你需要下载以下文件：

 - adbd 文件
 - Magisk 20400
 - XTCPatch 2100
 - 对应机型的 mbn 文件

<!-- :::note
Magisk 25200 为普通版本的 Magisk，而 25210 则为 Magisk Delta(也称为 Kitsune)。如果你不知道如何选择则选择 25200 即可
::: -->

而如果你的手表是高版本，则你需要下载以下文件：

 - adbd 文件
 - Magisk 25200
 - XTCPatchFor810
 - Xposed
 - Userdata 镜像
 - mbn 文件

你需要 [在这里](https://share.onesoft.top/s/d1eb6f5525b34ee6ba) 下载所需的文件。

下载完成后，你可以开始下一步 [提取 BOOT 分区](./get-boot-partition)