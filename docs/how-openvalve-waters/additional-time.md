---
title: Additional Time
sidebar_position: 3
description: "Learn how the Additional Time setting affects watering."
---
# Additional Time

The Additional Time is a device setting that defines how much longer OpenValve keeps watering after water reaches the sensor.

When OpenValve opens, it starts measuring how long it takes until the soil moisture at the sensor rises above the Opening Threshold. This time tells OpenValve how long it took for the water to reach the sensor.

OpenValve then uses the Additional Time setting to decide whether it should stop watering or keep the valve open longer.

The setting can be changed from **1 to 5**:

| Setting | Extra watering time |
| ------- | ------------------: |
| 1       |       no extra time |
| 2       |                +50% |
| 3       |               +100% |
| 4       |               +150% |
| 5       |               +200% |

## Example:

If it takes **10 minutes** until water reaches the sensor:

* Additional Time **1** → valve closes immediately -> total watering time is **10 minutes**
* Additional Time **2** → total watering time is **15 minutes**
* Additional Time **3** → total watering time is **20 minutes**
* Additional Time **4** → total watering time is **25 minutes**
* Additional Time **5** → total watering time is **30 minutes**

Use a low value if watering should stop immediately or soon after the water reaches the sensor. In this case, the soil around the sensor gets wet, but the valve closes before much more water can move deeper or spread farther.

Use a higher value if you want the valve to stay open longer after water reaches the sensor. Imagine the sensor as the first checkpoint: once water arrives there, OpenValve can either stop soon, or keep watering so the wet area can grow deeper and wider.

**Important:** Additional Time is only added while OpenValve is in sleep mode. If you wake OpenValve by pressing the button, it reacts immediately to sensor changes and ignores the Additional Time setting.