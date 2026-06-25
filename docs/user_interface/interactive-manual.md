---
title: Interactive Manual
sidebar_position: 2
description: "A fun and hands-on approach to get familiar with OpenValve"
---


The Interactive Manual is a browser-based version of the OpenValve user interface. It lets you explore the button interactions, LED patterns, settings, and state transitions without having the physical device in front of you.

## Before you begin

* The Interactive Manual intentionally has no **Back** or **Undo** button. This may feel limiting at first, but it reflects how the real device works: OpenValve has only one button, and every UI state can be reached through button presses. To reset the Interactive Manual completely, refresh the page.

* The **Opening Threshold** and **Current Soil Moisture** settings affect how the virtual device behaves. For example, in the **Display Current Soil Moisture** state, changing the soil-moisture slider opens and closes the valve depending on the configured Opening Threshold.

* The real OpenValve automatically returns to the **Sleep** state after one minute without a button press. This is called the UI timeout. The Interactive Manual does not use this timeout, so you can explore the interface without being interrupted.

## Current limitations

The Interactive Manual does not yet reproduce every behaviour of the real device.

* The **Additional Time** setting currently has no practical effect.
* Behaviour in sleep state does not yet match the real device.
* Warnings and error states are not yet included.
* The firmware version is not yet shown when turning OpenValve on from the **Off** state.

**[Open the Interactive Manual →](https://ui.open-valve.com)**


