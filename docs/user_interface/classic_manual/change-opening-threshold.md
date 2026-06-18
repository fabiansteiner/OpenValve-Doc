---
title: "State: Change Opening Threshold"
sidebar_position: 7
description: "Change Opening Threshold"
---
# State: Opening Threshold

This state is used to change the [**Opening Threshold**](./../../how-openvalve-waters/opening-threshold).

The current Opening Threshold is [shown by the number of green LED blinks](./../basics#led-pattern-to-show-numbers). The value can be between 1 and 8. The Opening Threshold defines how dry the soil must become before the next irrigation starts.

If the current soil moisture is at or below the Opening Threshold, the valve opens. If the current soil moisture is above the Opening Threshold, the valve closes.

:::info

Changes don´t have to be explicitely saved or accepted.

:::

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | no state change| Increment the Opening Threshold value by 1. After the highest value, it wraps around. |
| Long press | [Sleep](./sleep) | Return to Sleep. |
