---
title: "Data Acquisition Mode"
sidebar_position: 17
---

![](/img/en-img/CommonSettings/DataAcquisitionMode/0.png)

The software supports three data acquisition modes: time-interval photo capture, distance-interval photo capture, and video recording.

For industrial drones, all three data acquisition modes require only a small number of waypoints and will not cause remote controller lag.

For consumer drones:
- Distance-interval photo capture inserts a waypoint at fixed intervals. It requires a large number of waypoints and may cause remote controller lag.
- Time-interval photo capture requires only a small set of key waypoints. However, you must manually enable timed photo capture on the remote controller when the aircraft reaches the first waypoint; auto-enable is not supported.
- Video recording requires only a small set of key waypoints with no manual operation, making it a preferred data acquisition method.

:::tip
Gimbals require time to capture photos (ranging from 0.3s/shot to 3s/shot). Combined with data overlap requirements, the maximum flight speed limit for both photo capture modes is determined by the gimbal’s fastest shooting speed.

Since capturing each photo takes time (ranging from 0.7 to 3 seconds per shot), and a certain data overlap is required, the maximum flight speed for both photo-based data collection methods is determined by the fastest photo capture rate.

When recording video, the system assumes a fastest capture rate of 0.7 seconds per shot and uses this to determine the maximum flight speed.
:::