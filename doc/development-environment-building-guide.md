## 开发环境搭建指南

### 1. 安装并配置 git 工具

### 2. 获取最新源码

### 3. 配置编译

和 kernel 等工程一样，编译之前需要先配置工程

    make menuconfig

第一次执行可能会报错 “找不到 curses.h”，需要安装 ncurses 基本库。

    sudo apt-get install libncurses5-dev

> 备注：ncurses 是字符终端下屏幕控制的基本库。可能很多新开发的程序都不使用了，不过如果要编译一些老程序，还经常遇得到。编译 kernel 和 u-boot 时 make menuconfig 命令就需要这个库。

### 4. 烧写验证

## 加入我们

### 1. 创建一个 github

### 2. 申请加入 esJZ2440 组织