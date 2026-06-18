---
title: "State: Display Current Soil Moisture"
sidebar_position: 3
description: "Display Current Soil Moisture state explained"
---
# State: Display Current Soil Moisture

This state shows the current soil moisture measured by the sensor.

The current soil moisture level is [indicated by the number of green LED blinks](./../basics#led-pattern-to-show-numbers). The value can be between **1** and **9**. A value of **1** means the soil is extremely dry. A value of **9** means the soil is very wet or saturated.

The blink value corresponds to the approximate volumetric water content (VWC) measured by the sensor:

| LED blinks | VWC |
| :---: | :---------: |
|1 |`< 12%` |
|2 |`> 12%` |
|3 |`> 16%` |
|4 |`> 20%` |
|5 |`> 24%` |
| 6 | `> 28%` |
| 7 | `> 32%` |
| 8 | `> 36%` |
| 9 | `> 40%` |

OpenValve compares this measured soil moisture value with the configured [**Opening Threshold**](./../../how-openvalve-waters/opening-threshold). The valve opens whenever the current soil moisture is less than or equal to the Opening Threshold.


## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | [Display Battery Level](./display-battery-level) | Go back to the battery level display. |
| Long press | [Manually Open](./manually-open) | If currently closed the valve opens. |
| Very long press | [Off](./off) | Turn OpenValve off. |
