---
title: "Warnings"
sidebar_position: 11
description: "Warnings explained"
---
# Warnings

OpenValve shows warnings while it is in the Sleep state and the valve is closed. When a warning is active, the upper LED blinks orange every 30 seconds.

Warnings do not mean that OpenValve has stopped working. They indicate that something needs attention soon.

There are two possible warnings:

| Warning | Meaning | How to clear it |
| --- | --- | --- |
| Battery low | The battery will be empty soon. | Replace the battery. |
| Silicone hose replacement | The silicone hose inside the pinch valve has reached more than 1450 valve cycles and should be replaced soon. | Replace the silicone hose, then reset the hose warning manually. |

## Checking which warning is active

Both warnings are shown in the same way: the upper LED blinks orange every 30 seconds.

To find out which warning is active, wake OpenValve by pressing the button. This switches OpenValve to the [Display Battery Level](./display-battery-level) state.

If the battery level is shown as **red blinking**, the warning is caused by a low battery. Replace the battery to clear the warning.

If the battery level is **not red blinking**, the warning is caused by the silicone hose cycle counter. This means the valve has opened and closed more than **1450 times**, and the silicone hose inside OpenValve should be replaced soon.

:::note
A specific guide for how to replace the silicone hose will be available soon. For now refer to the assembly guide.
:::

## Resetting the silicone hose warning

The silicone hose warning does not reset automatically. After replacing the silicone hose, the warning must be reset manually.

To reset the silicone hose warning:

1. Unplug the battery.
2. Press and hold the button.
3. **While holding the button pressed**, plug the battery in. (all LEDs start blinking rapidly)
4. **Do not release the button yet.** Keep holding it (for ~15 seconds) **until the blink pattern changes** from rapidly blinking all LEDs to blinking orange slowly.
5. OpenValve slowly blinks orange 3 times, which means the reset was succesful.






