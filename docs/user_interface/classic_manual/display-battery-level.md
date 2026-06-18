---
title: "State: Display Battery Level"
sidebar_position: 2
description: "Display Battery Level state explained"
---
# State: Display Battery Level

This state shows the current battery level of OpenValve.

The upper LED displays the battery status. The LED color gives a rough estimate of how much operating time is left:

| Upper LED    | Meaning              | Estimated remaining operating time |
| ------------ | -------------------- | ---------------------------------- |
| Green        | Battery full (> 8.5V)         | More than 2 months                 |
| Orange       | Battery medium (> 8.0V)       | More than 1 month                  |
| Red          | Battery low  (> 7.5V)        | Less than 1 month                  |
| Red blinking | Battery almost empty (< 7.5V) | Very little time remaining         |


When the battery is completely empty, OpenValve switches to an [error state](./error-state) and will not water again until the battery has been replaced.

:::warning
If the battery becomes completely empty, OpenValve will stop watering until the battery is replaced.
:::


## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | [Display Current Soil Moisture](./display-current-soil-moisture) | Show the current soil moisture value. |
| Long press | [Select Opening Threshold](./select-opening-threshold) | Enter the irrigation settings selection. |
| Very long press | [Off](./off) | Turn OpenValve off. |
