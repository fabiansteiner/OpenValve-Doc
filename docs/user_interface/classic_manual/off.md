---
title: "State: Off"
sidebar_position: 9
description: "Off state explained"
---
# State: Off

Switching OpenValve to the Off state closes the valve and stops normal operation.

While OpenValve is off, it does not perform automatic soil-moisture-based irrigation.

To turn OpenValve back on, perform a **very long press**. Before switching to the next state, OpenValve displays its current firmware version using the LEDs:

1. The **major version number** is shown by red blinks.
2. The **minor version number** is shown by green blinks.

For example, two red blinks followed by three green blinks indicate firmware version **2.3**.

After showing the firmware version, OpenValve switches to the **Display Battery Level** state.

## State transitions

| Button action   | Next state                                       | What happens                                                                   |
| --------------- | ------------------------------------------------ | ------------------------------------------------------------------------------ |
| Very long press | [Display Battery Level](./display-battery-level) | Displays the current firmware version, then switches to Display Battery Level. |

