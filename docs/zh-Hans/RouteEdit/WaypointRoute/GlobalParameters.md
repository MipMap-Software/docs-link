---
title: "全局参数"
sidebar_position: 4
---
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-0.png)

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-1.png)

创建航点航线进入编辑页后，点击左侧![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-2.png)按钮，即可设置航点航线的全局参数，不同设备可设置的全局参数存在差异，支持的参数值也有所不同，以各个机型实际情况为准，此处仅介绍常用设置项



机型切换后，软件将自动检查当前机型不支持的参数/参数值，并进行修正



## 相对起飞点
必须设置参考起飞点才能编辑航点

**\* 此处设置的相对起飞点仅为参考值，行业级/消费级无人机将以起飞时的坐标作为相对起飞点**

**\* 目前消费级无人机仅支持"相对起飞点"高度模式，因此参考起飞点应尽量与实际起飞点保持高程一致！**

****

首次创建航线时，鼠标左建单击地图即可设置参考起飞点，若参考起飞点已设置，可点击"重设起飞点"以重置相对起飞点![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-3.png)



相对起飞点支持平移、调整高度，在地图上使用鼠标左建点击相对起飞点图标，以此选中并激活相对起飞点

在激活态下，鼠标左键按下相对起飞点，再移动鼠标，即可平移相对起飞点，鼠标左键松开时完成编辑

在激活态下，Alt+鼠标左键按下相对起飞点，再移动鼠标，即可调整相对起飞点的高程，鼠标左键松开时完成编辑

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-1.gif)



## 执行设备
点击![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-4.png)可修改执行设备，设备修改后，软件将自动进行参数可用性、动作可用性检查，当前设备不支持的参数、动作将被移除，因此建议修改设备前使用"复制航线"的功能将航线备份

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-5.png)



## 全局拍摄照片
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-6.png)

可设置拍照动作默认拍摄哪些类型的照片，选中多个时，动作执行时将拍摄多种类型的照片



## 是否开启全局智能低光
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-7.png)

开启后，所有定向拍照动作的智能低光将被启用，反之所有定向拍照动作的智能低光都将被禁用



## 起飞爬升模式及安全起飞高度
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-8.png)可设置飞行器从起飞点起飞时垂直爬升到首航点还是倾斜爬升到首航点

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-9.png)可设置安全起飞高度



## 航线高度模式
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-10.png)

可在此处设置航线高度模式

**\* 目前消费级无人机只支持"相对起飞点"高度模式，消费级无人机航线在写出时，程序会在内部将所有航点和兴趣点转换为"相对起飞点高"，因此建议将相对起飞点高度设置为实际起飞点高度**

"相对地形"高度模式指规划航线时，航点高度默认相对**地图地形（非现实实际地形）**xx米，**并不是指实时仿地，航点间航段飞行不会考虑地形高度，航线实际按WGS84高执行**

****

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-11.png)

可在此处设置全局航点高度，航点添加时默认使用全局高度

## 全局航线速度
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-12.png)设置全局航线飞行最大速度，航点未单独设置速度时，将使用此速度在航点间飞行



## 起飞速度
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-13.png)设置飞行器从起飞点飞向首航点时的最大速度



## 全局航点类型
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-14.png)

此处设置全局航点类型，不同机型支持的航点类型有所不同，面对不同航点类型，飞行器在执行航线时的路径有所不同，到点停的航线更费电，因为飞行器需要刹停，到点不停的航线更省电

### 协调转弯：
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-15.png)

飞行器不会经过航点，而是提前转弯

### 直线飞行：
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-16.png)

飞行器沿直线飞行

### 平滑过点：
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-17.png)

飞行器会经过航点，但不会直线经过航点，而是会提前一段距离转弯

### 曲线飞行：
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-18.png)

飞行器使用贝塞尔曲线进行飞行

#### * 曲线飞行在航点高程相差较大时，航段可能出现下弯引起高程下降，该特性可能引发飞行事故，建议规划航线时仔细检查各航段
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-19.png)

（曲线飞行航段间的高程下降）

## 全局飞行器偏航角
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-20.png)

此处设置全局飞行器偏航方向，飞行器在航段间执行时，默认将按此设置控制机头方向，若航点单独设置了此属性，则以单独设置项为准



## 全局云台俯仰角
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-21.png)

此处设置全局云台俯仰角，飞行器在航段间执行时，默认将按此设置控制云台俯仰角，若航点单独设置了此属性，则以单独设置为准


## 航线执行完成后默认动作
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-22.png)

此处设置航线执行完成后飞行器的默认动作，该默认行为可被人为打断/修改



## 飞行器失控动作
![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-23.png)

此处设置飞行器执行航线过程中失去与A控/B控联系后的动作，为保障设备安全，建议设置为"返航"，其他选项可能导致设备丢失



## 保存航线
程序不会自动保存航线，参数、航点等修改确认完毕后，需要点击![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-24.png)保存数据，航线保存时将自动生成、更新航线预览图，预览图使用正交相机+俯视生成

存在数据修改且未保存变更时，若退出页面，将提示数据未保存

![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-25.png)



没有待保存数据时，![](/img/RouteEdit/WaypointRoute/GlobalParameters/image-26.png)保存按钮将不可点击

