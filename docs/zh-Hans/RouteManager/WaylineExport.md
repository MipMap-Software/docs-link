---
title: "航线导出"
sidebar_position: 4
---
![](/img/RouteManager/WaylineExport/image-1.png)

软件可将航线导出至本地或Dji Fly/移动存储，导出内容为航线kmz文件，若是本地导出，导出内容还包含航线测区kml、未插值飞行轨迹kml

### 航线拆分
![](/img/RouteManager/WaylineExport/image-3.png)

启用航线拆分时，程序会导出多个航线kmz文件，并通过一系列算法确保各个子航线的飞行姿态、录像任务等与原始单航线保持一致

### 导出航线至移动设备
![](/img/RouteManager/WaylineExport/image-4.png)

在航线导出面板设置好分割参数后，点击此处，可跳转至航线快捷导出至移动设备面板

### 普通移动设备（未安装DJI Fly / DJI Pilot）
![](/img/RouteManager/WaylineExport/image-5.png)

对于普通设备，软件可自动将航线 / 航线切片导出至 内部存储 或 内部存储/Download

### DJI Pilot
DJI Pilot有航线导入功能，因此使用软件直接导出到 内部存储/Download 或者手动复制转移即可，而后在DJI Pilot内导入航线

### DJI Fly

#### 自动替换
DJI Fly 没有航线导入功能，只能通过替换原有航线，实现“导入”的效果，软件提供了快捷替换导出的功能（仅支持DJI RC或安卓设备）

![](/img/RouteManager/WaylineExport/image-7.png)

将 带屏遥控器 / 安装了DJI Fly的安卓设备 通过USB连接电脑，选择文件传输模式，软件将列出DJI Fly现有的航线，选择待替换的航线，点击导出，软件将自动执行缩略图替换、航线文件替换

:::tip
DJI Fly航线列表可能存在缩略图缓存，为确保后续正确辨认航线，需要刷新缓存

在DJI Fly航线列表找到被替换的航线，重命名航线并保存，即可刷新缩略图缓存
:::

#### 手动替换
当设备无法识别，或设备为ios时，需要手动替换实现航线导入，将设备通过USB与电脑连接，通过资源管理器，前往 DJI Fly 航线存储路径，进行航线替换，如安卓设备：

![](/img/RouteManager/WaylineExport/image-8.png)

在 Android\data\dji.go.v5\files\waypoint\ 目录，选择一个待替换航线（如 1ABD4443-82FC-4FE4-8C0A-DE986951C2A7 ），将软件生成的kmz文件复制进文件夹，删除原始 1ABD4443-82FC-4FE4-8C0A-DE986951C2A7.kmz 航线，将复制进入的kmz重命名为 1ABD4443-82FC-4FE4-8C0A-DE986951C2A7.kmz

IOS步骤一致，但IOS航线文件目录为：DJI Fly\wayline_mission\
