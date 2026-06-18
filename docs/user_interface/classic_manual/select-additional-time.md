---
title: "State: Select Additional Time"
sidebar_position: 6
description: "Select Additional Time state explained"
---
# State: Select Additional Time

In this state the upper LED is blinking orange rapidly.

This state is used to choose which irrigation setting should be changed.

When OpenValve is in this state, the next long press will switch to the state where the [Additional Time](./../../how-openvalve-waters/additional-time) can be adjusted.

## State transitions

Use this table to see where OpenValve can go from this state.

| Button action | Next state | What happens |
| --- | --- | --- |
| Short press | [Select Opening Threshold](./select-opening-threshold) | Switch the selection back to Opening Threshold. |
| Long press | [Change Additional Time](./change-additional-time) | Open the state for changing the Additional Time. |
| Very long press | [Off](./off) | Turn OpenValve off. |
