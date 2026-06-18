---
title: "State: Manually Open"
sidebar_position: 4
description: "Manually Open state explained"
---
# State: Manually Open

In this state the blue LED is blinking.

Switching to this state opens the valve regardless of the current soil moisture. This is useful for immediate watering, testing the irrigation system, or checking whether water reaches the intended emitters.

The valve can be closed again by pressing the button or it closes automatically after 15 minutes.

## State transitions

Use this table to see where OpenValve can go from this state.

| Action | Next state | What happens |
| --- | --- | --- |
| Short press | [Display Current Soil Moisture](./display-current-soil-moisture) | Close the valve and show the current soil moisture. |
| 15 minutes passed | [Display Current Soil Moisture](./display-current-soil-moisture) | Closes the valve automatically and returns to the soil moisture display. |
| Very long press | [Off](./off) | Turn OpenValve off. |
