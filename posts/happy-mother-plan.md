---
title: 智能家庭（需求）
date: '2013-03-16'
description:
categories:
- 2013
- blog
- plan
tags:raspberry pi 智能
---

准备开始完成自己的智能家庭计划（自我定义，请勿吹毛求疵）！

{:toc}

###	基本需求如下

	语音控制、语音播报
	监控室内温度和湿度（包括：气象台发布的，通过网络抓取），并设置报警，提醒穿衣
	播放家庭计划，比如：几月几号需要给小宝打疫苗	
	通过Ipad1做信息展示端
	通过语音遥控家电，比如：打开电视机到特定频道、打开空调
	通过继电器打开自带的灯（无法对现有线路进行改造）
	可遥控的摄像头
	远程语音聊天


###	预计采用的硬件设备

	树莓派（自带声卡）
	温度、湿度传器
	二度自由舵机+摄像头
	Microphone以及USB外置声卡（完成语音输入）
	继电器+台灯
	Ipad1
	红外线接收和发射器

###	预计采用的软件

	Julius语音识别
	Go语言（哎，又要学习一个新的）
	存储用sqlite或者文件
	其他的再说


###	预计实现计划

	先完成语音识别的工作，否则一切白搭
	室内温度和湿度的监控和播报
	其他慢慢来


PS：在倒立工坊也可以实现类似的东西



	

