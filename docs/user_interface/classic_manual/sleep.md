---
title: "State: Sleep"
sidebar_position: 1
description: "Sleep state explained"
---
# State: Sleep

Sleep is the normal operating state of OpenValve. This is the state OpenValve will be in most of the time, and it is also the default state after the battery is plugged in.

In this state, OpenValve automatically opens and closes the valve according to the configured [**Opening Threshold**](./../../how-openvalve-waters/opening-threshold) and [**Additional Time**](./../../how-openvalve-waters/additional-time) settings.

To save battery, OpenValve does not measure soil moisture continuously while it is sleeping. Instead, it takes measurements at fixed intervals depending on the valve state:

| Valve state                  | Measurement interval              |
| ---------------------------- | --------------------------------- |
| Valve closed                 | Every 1 hour                      |
| Valve open, first 3 minutes  | Every 4 seconds                   |
| Valve open, after 3 minutes  | Every 16 seconds until 10 minutes |
| Valve open, after 10 minutes | Every 60 seconds                  |

Every time a new soil moisture measurement is taken, the blue LED blinks briefly.

In the Sleep state, OpenValve also shows [warnings](./warnings) by blinking the orange LED once per minute while the valve is closed.

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state                                              | What happens                                            |
| ------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| Short press   | [Display Battery Level](./display-battery-level) | OpenValve wakes up and shows the current battery level. |
