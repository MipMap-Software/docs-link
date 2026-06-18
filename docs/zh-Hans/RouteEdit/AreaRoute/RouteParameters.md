---
title: "航线参数"
sidebar_position: 2
---

![](/img/RouteEdit/AreaRoute/RouteParameters/image-0.png)

![](/img/RouteEdit/AreaRoute/RouteParameters/image-1.png)

![](/img/RouteEdit/AreaRoute/RouteParameters/image-2.png)



创建面状航线进入编辑页后，即可设置航线参数，不同设备可设置的参数存在差异，支持的参数值也有所不同，以各个机型实际情况为准，此处仅介绍常用设置项



机型切换后，软件将自动检查当前机型不支持的参数/参数值，并进行修正



## 相对起飞点
必须设置参考起飞点才能绘制测区、调整GSD

**\* 此处设置的相对起飞点仅为参考值，行业级/消费级无人机将以起飞时的坐标作为相对起飞点**

**\* 目前消费级无人机仅支持"相对起飞点"高度模式，因此参考起飞点应尽量与实际起飞点保持高程一致！**

****

首次创建航线时，鼠标左建单击地图即可设置参考起飞点，若参考起飞点已设置，可点击"重设起飞点"以重置相对起飞点![](/img/RouteEdit/AreaRoute/RouteParameters/image-3.png)



相对起飞点支持平移、调整高度，在地图上使用鼠标左建点击相对起飞点图标，以此选中并激活相对起飞点

在激活态下，鼠标左键按下相对起飞点，再移动鼠标，即可平移相对起飞点，鼠标左键松开时完成编辑

在激活态下，Alt+鼠标左键按下相对起飞点，再移动鼠标，即可调整相对起飞点的高程，鼠标左键松开时完成编辑

![](/img/RouteEdit/AreaRoute/RouteParameters/image-0.gif)



## 执行设备
点击![](/img/RouteEdit/AreaRoute/RouteParameters/image-4.png)可修改执行设备，设备修改后，软件将自动进行参数可用性检查，当前设备不支持的参数将被移除，因此建议修改设备前使用"复制航线"的功能将航线备份



## 工作镜头
![](/img/RouteEdit/AreaRoute/RouteParameters/image-5.png)

可设置航线执行过程中使用哪些镜头拍摄照片，选中多个时，执行航线中将拍摄多个镜头的照片



## 采集方式
![](/img/RouteEdit/AreaRoute/RouteParameters/image-6.png)

可设置飞行时正射采集照片还是倾斜采集照片



## GSD
![](/img/RouteEdit/AreaRoute/RouteParameters/image-7.png)

规划航线时，程序将计算当前航线的GSD（照片内每个像素代表的实际地面距离），可手动调整GSD来影响飞行高度，或手动调整高度来影响GSD

GSD越小，图像分辨率越高，但飞行器距离被测面也越近，设备安全风险提升

GSD越小，设备可用的最大飞行速度也越低，可能大幅增加航线执行时间



## 航线高度模式及飞行高度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-8.png)

此处可设置航线高度模式，目前消费级无人机仅支持"相对起飞点"高度模式，其他高度模式在生成航线时，将在内部转换为"相对起飞点"高，因此建议相对起飞点高程与实际起飞点高程保持一致

![](/img/RouteEdit/AreaRoute/RouteParameters/image-9.png)

此处设置航线飞行高度

## 安全起飞高度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-10.png)

此处可设置安全起飞高度，飞行器将先抬升到此高度，再执行航线



## 全局航线速度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-11.png)

设置全局航线飞行最大速度，飞行器将使用此速度执行航线



## 主航线角度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-12.png)

![](/img/RouteEdit/AreaRoute/RouteParameters/image-13.png)

此处可控制生成航线时主航线的角度（正北为0）

## 高程优化
![](/img/RouteEdit/AreaRoute/RouteParameters/image-14.png)

此处可设置是否开启高程优化，开启后，飞行器将在正射航线执行完成后飞向测区中心拍摄一组倾斜照片



****

## 航线执行完成后默认动作
![](/img/RouteEdit/AreaRoute/RouteParameters/image-15.png)

此处设置航线执行完成后飞行器的默认动作，该默认行为可被人为打断/修改



## 起飞速度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-16.png)

此处设置飞行器从起飞点飞向首航点/从航线1飞向航线2时的飞行速度

## 被摄面高度
![](/img/RouteEdit/AreaRoute/RouteParameters/image-17.png)

此处可设置被摄面高度，被摄面高度会影响GSD及航线计算

被摄面在地图上显示为橙色区域，默认情况下，被摄面高度为首次设置相对起飞点时的起飞点高度



## 旁向重叠率
![](/img/RouteEdit/AreaRoute/RouteParameters/image-18.png)

此处可设置航线旁向重叠率（与飞行器飞行方向相垂直的方向），重叠率越高，越有利于建模

## 航向重叠率
![](/img/RouteEdit/AreaRoute/RouteParameters/image-19.png)

此处可设置航线航线重叠率（飞行器飞行方向），重叠率越高，越有利于建模，**但会限制最大可飞行速度**

## 测区外扩距离
![](/img/RouteEdit/AreaRoute/RouteParameters/image-20.png)

此处可设置测区外扩距离，软件将以外扩后的测区计算航线，该功能可确保测区边缘重叠度足够高，确保重建软件正确处理测区边缘

## 拍照模式
![](/img/RouteEdit/AreaRoute/RouteParameters/image-21.png)

此处可设置飞行器是按等时间间隔拍照还是按等距离间隔拍照

## 飞行器失控动作
![](/img/RouteEdit/AreaRoute/RouteParameters/image-22.png)

此处设置飞行器执行航线过程中失去与A控/B控联系后的动作，为保障设备安全，建议设置为"返航"，其他选项可能导致设备丢失



## 生成并保存航线
程序不会自动生成/保存航线，参数修改确认完毕后，需要点击![](/img/RouteEdit/AreaRoute/RouteParameters/image-23.png)生成新航线并保存设置数据，航线保存时将自动生成、更新航线预览图，预览图使用正交相机+俯视生成

存在数据修改且未保存变更时，若退出页面，将提示数据未保存

![](/img/RouteEdit/AreaRoute/RouteParameters/image-24.png)

没有待保存数据时，![](/img/RouteEdit/AreaRoute/RouteParameters/image-25.png)保存按钮将不可点击

