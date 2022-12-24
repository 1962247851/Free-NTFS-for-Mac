# Nigate（Free NTFS for Mac）

Nigate，苦手（ニガテ），一款macOS平台免费开源的NTFS小程序应用app。

小工具制作原由：

Mac平台下支持的NTFS软件，普遍收费。免费的难找，就算找到了，有的也不支持最新的macOS，又或是arm芯片不支持...macfuse，对于一个普通用户来说，上手门槛又实在有些高了...整体的体验上不太让人舒服。尤其是对于我们做计算机维护的人来说，更是如此了。

## 💻 实机演示

视频：https://www.bilibili.com/video/BV1XG4y1f79N/

(演示优盘是公司测试用的，usb2.0接口，所以拷贝速度比较慢)

![Watch the video](https://fastly.jsdelivr.net/gh/hoochanlon/free-mac-ntfs/shashin/example.png)


## ⚠️ 需关闭SIP进行安装及使用

[关机后长按开机键，进入“恢复”环境，在“实用工具”->“启动安全性实用工具”降低安全性的选项全都都勾上（出现不能更改安全性设置，关机盒盖，30秒后再操作一遍即可）](https://www.pcbiji.com/212402.html)。

这是安装使用学习版软件和系统扩展插件的常规操作，你懂的，基本上知道这个也方便像windows那样使用软件了。

## ⏬ Mac app下载

* 首次运行软件，程序会检测所需要的集成环境，并自动下载安装（之后不用了）。
* 运行软件保持在后台，插入U盘即可。

由 ghproxy 加速下载支持：

https://ghproxy.com/https://github.com/hoochanlon/Free-NTFS-for-Mac/releases/download/0.1/nigate.dmg

## 🧑‍🔧 桌维技术支持版(脚本)

1. 在“shell_for_helpdesk”文件夹，找到 “自动化支持NTFS读写.sh” 下载
2. 在终端授权脚本文件，如：`chmod 777 自动化支持NTFS读写.sh`。
3. 在终端下直接 `自动化支持NTFS读写.sh` 回车输入密码即可（只需输入一遍）。

## ❤️ 感谢

提供集成应用支持与图标设计样例。

* [osxfuse](https://osxfuse.github.io)
* [sveinbjorn.org](https://sveinbjorn.org/platypus) 
* [langui.net](https://langui.net/new-file-menu/)
* [cunkai/HomebrewCN](https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)
* [ineo6/homebrew-install](https://gitee.com/ineo6/homebrew-install/raw/master/install.sh)
* [qastack](https://qastack.cn) | [icons8](https://icons8.com) | [gofans](https://gofans.cn)
