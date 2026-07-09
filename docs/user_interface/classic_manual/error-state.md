---
title: "State: Error State"
sidebar_position: 10
description: "Error State explained"
---
# State: Error State

The error state indicates that OpenValve detected a problem and stopped normal operation.

When an error occured and OpenValve is in sleep mode, the red LED briefly blinks every 4 seconds to indicate that an error is active and raise attention.

To find out **which** error occurred, press the button. OpenValve will then show the error code using [the number of red LED blinks](./../basics#led-pattern-to-show-numbers).

:::warning

Do not confuse an almost empty battery with an error state. if the User Interface can be normally navigated and the red blinking is slow and ryhtmic, that only means that the [battery is almost empty](./display-battery-level).

:::

| Blinks | Meaning | Cause | Solution | 
| ------- | ------------------ | ------------------ |------------------ |
|      1 | No water detected at the sensor after 120 minutes of watering. The valve was closed for safety reasons.  | Bad sensor placement, empty water source, closed tap, blocked hose, or another problem with the water supply.| Long press to exit the error state. Then check the water source, hose, emitter, and sensor position. |
|      2 | Battery fully depleted.| Battery voltage got too low (`<4 V` while closing or `<7 V` before opening).| Replace the battery.|
|      3 | Motor current was too high while closing the valve.| Water pressure may be too high. Other possible causes are a damaged end stop button, deformed housing or links, broken motor gears, or problems with the motor brushes or coils. | Check whether the water pressure is too high. Unplug the battery, partially disassemble OpenValve, reconnect the battery, and observe the exact behaviour while opening and closing. Adjusting the slider position may help if the link arm does not reach the end stop button correctly. |
|      4 | Valve timeout. The motor was running for a certain amount of time, but the valve did not open or close. | Possible causes are damaged motor gears, a soldering error on the PCB, disconnected motor cables, or a malfunctioning motor driver IC. This can also happen if OpenValve tries to open or close while the links are not connected to the motor yet. | Unplug the battery, partially disassemble OpenValve, reconnect the battery, and observe the exact behaviour while opening and closing. |

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state                                       | What happens                                                              |
| ------------- | ------------------------------------------------ | ------------------------------------------------------------------------- |
| Long press    | [Display Battery Level](./display-battery-level) | Only for error code 1: exits the error state and shows the battery level. |

