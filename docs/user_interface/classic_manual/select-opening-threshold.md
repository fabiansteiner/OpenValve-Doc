---
title: "State: Select Opening Threshold"
sidebar_position: 5
description: "Select Opening Threshold state explained"
---
# State: Select Opening Threshold

In this state the upper LED is blinking green rapidly.

This state is used to choose which irrigation setting should be changed.

When OpenValve is in this state, the next long press will switch to the state where the [Opening Threshold](./../../how-openvalve-waters/opening-threshold) can be adjusted.

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | [Select Additional Time](./select-additional-time) | Switch the selection to Additional Time. |
| Long press | [Change Opening Threshold](./change-opening-threshold) | Open the state for changing the Opening Threshold. |
| Very long press | [Off](./off) | Turn OpenValve off. |
