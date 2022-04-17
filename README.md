## Garabage Detection with WUKONG-Robot

###### Arthor: 19182638 19182655 19182641 1918263 (BUAA Sno)

BUAA Android平台开发技术课程项目代码，作者为 LD, Ariza，kkkkk，Edward。

对于本项目，需要有悟空机器人硬件支持。本代码采用 GPLv2 License 协议。



## Startup：

悟空机器人绑定，server 端启动，phone 端 **或** alphaMini 端通过局域网远程通信启动操作。



本项目有项目演示效果视频，链接如下：

> https://bhpan.buaa.edu.cn:443/link/FA4F337AE645CD1B17CF9B94E5C10DF0
>
> 有效期限：2024-01-12 23:59



## Description

本项目现有代码端：**master, phone, server, alphaMini**。由于不同端开发语言并不相同，开发套件也不同，因此完整开发需要装有 `Pycharm`、`Android Studio`、`IDEA`（3个版本分别为 2021.3、2020.3、2021.3），由此我们把不同功能做到不同的仓库，通过 submodule 统一管理。



不同 submodule 下都有对应的 commit 编号和 README.md，有对应的使用说明。下面对不同分支进行说明：

`phone` 端：安卓用户端代码。

`server` 端：电脑服务端代码。

`alphaMini` 端：电脑悟空平台代码。