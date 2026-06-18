---
title: "State: Change Additional Time"
sidebar_position: 8
description: "Change Additional Time state explained"
---
# State: Change Additional Time

This state is used to change the [**Additional Time**](./../../how-openvalve-waters/additional-time).

The current Additional Time setting is [shown by the number of orange LED blinks](./../basics#led-pattern-to-show-numbers). The value can be between 1 and 5. This setting affects how the valve closes in [Sleep state](./sleep).

A value of 1 means the valve closes immediately when water reaches the soil moisture sensor and the measured soil moisture rises above the Opening Threshold. Each higher value increases the time the valve remains open by an additional 50% after the threshold is exceeded.

For example, if water takes 10 minutes to reach the sensor and the Additional Time is set to 3, OpenValve keeps the valve open for an additional 100% of that time. In this example, the total watering time would be 20 minutes.

:::info

Changes don´t have to be explicitely saved or accepted.

:::

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | no state change | Increment the Additional Time value by 1. After the highest value, it wraps around. |
| Long press | [Sleep](./sleep) | Return to Sleep. |
