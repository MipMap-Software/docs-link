---
title: "航点类型"
sidebar_position: 19
---

![](/img/SharedSets/PointType/0.png)

此设置项仅对航点航线有效，设置全局航点类型，不同机型支持的航点类型有所不同，面对不同航点类型，飞行器在执行航线时的路径有所不同，到点停的航线更费电，因为飞行器需要刹停，到点不停的航线更省电

### 1. 协调转弯
![](/img/SharedSets/PointType/1.png)

飞行器不会经过航点，而是提前转弯

### 2. 直线飞行
![](/img/SharedSets/PointType/2.png)

飞行器沿直线飞行

### 3. 平滑过点
![](/img/SharedSets/PointType/3.png)

飞行器会经过航点，但不会直线经过航点，而是会提前一段距离转弯

### 4. 曲线飞行
![](/img/SharedSets/PointType/4.png)

飞行器使用贝塞尔曲线进行飞行

:::warning
**曲线飞行在航点高程相差较大时，航段可能出现下弯引起高程下降，该特性可能引发飞行安全事故，建议规划航线时仔细检查各航段**

![](/img/SharedSets/PointType/5.png)

（曲线飞行航段间的高程下降）
:::