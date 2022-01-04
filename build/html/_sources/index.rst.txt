AutoPilot 使用文档
==============================

本文档AutoPilot无人车的在线资源平台，您可以在这里了解到所有关于R系列无人车的内容。

我们建议第一次使用无人车的朋友，先 **通读概述部分**，然后根据实际情况，找到对应的章节依次进行阅读。无人车使用及开发需要用户 **有一定技术基础**.

需要使用者掌握一定的 **Linux/ROS/C++/Python/PX4** 基本知识。如果您是第一次接触Linux或者ROS。请参考下面的链接，补充相关基础知识。

此产品为阿木实验室和松灵机器人共同研发，双方在称呼上有所差异，在松灵机器人代号为AutoPilot，在阿木实验室为R300,故在本说明中，不做单独说明，（AutoPilot）和R300 均为同一个产品。

其中:
   1. Linux需要掌握的知识有 `Linux系统文件结构及其常用命令 <https://www.runoob.com/linux/linux-file-content-manage.html>`_ 
   2. ROS需要掌握的知识有：ROS通信框架、gazebo仿真、TF等。非常建议大家去 `ROS官网 <http://wiki.ros.org/>`_ 学习
      或者前往B站，观看赵虚左老师的 `ROS教程 <https://www.bilibili.com/video/BV1Ci4y1L7ZZ?from=search&seid=3011252633328555279&spm_id_from=333.337.0.0>`_
   3. C++ / Python：ROS支持这两种开发语言。可以根据您个人的习惯，选择C++或者Python作为您的主要开发语言。 **R300大部分采用C++语言，只有少部分脚本采用Python语言编写**。
   4. PX4：AutoPilot具有室外导航及动态避障功能，该功能使用  `mavros <http://wiki.ros.org/mavros>`_ 作为通信协议。配合PX4飞控(飞控中使用的是APM Rover固件)，来实现该功能。


.. note::
   本手册由阿木实验室实时维护。若您有对本手册的内容有疑问，可以通过电子邮件或进入 `阿木社区 <https://bbs.amovlab.com/>`_ 通过发帖的方式向我们提问。若您希望对本手册提出修改意见，请发送邮件至service@amovauto.com，对于有建设性的意见我们将赠与阿木币！（阿木币可以1:1兑换成人民币）

.. note::
   本项目所有代码均开源！点击 `amovcar自主无人车项目 <https://gitee.com/amovlab/amovcar>`_ 可以下载项目源码。
   
   欢迎关注 `阿木实验室B站频道 <https://space.bilibili.com/432575320?from=search&seid=13705682698139641872>`_ 我们会在B站发布最新的、前言的科技视频以及有趣的测试视频。记得一键三连，不要下次一定！

祝您使用愉快！

`阿木实验室 <https://www.amovlab.com/zh-CN>`_ ，让研发更高效！

.. toctree::
   :maxdepth: 2
   :caption: 概述

   overview/概述
   overview/特点
   overview/组成
   overview/硬件模块介绍
   overview/硬件连接
   overview/通信链路
   overview/术语

.. toctree::
   :maxdepth: 2
   :caption: AutoPilot

   AutoPilot/快速上手指引
   AutoPilot/传感器校准
   AutoPilot/SLAM
   AutoPilot/导航
   AutoPilot/仿真



