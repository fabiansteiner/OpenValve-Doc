---
title: User Interface Basics
sidebar_position: 1
description: "The basics of how the User Interface of OpenValve works"
---

# User Interface Basics

OpenValve has a very minimalistic User Interface (UI). It uses only **one button for user input and two LEDs for output.**

The button is used for different actions depending on the current UI state and the type of button press:

* short press
* long press
* very long press

The LEDs show the current UI state and display information such as 

* valve state (opened/closed)
* battery level 
* current soil moisture
* current settings

### LED pattern to show numbers

Current soil moisture, Opening Threshold, Additional Time, and errors are represented by single-digit whole numbers. Because OpenValve only has LEDs and no display, these numbers are shown with a specific blinking pattern on the upper LED (either green, orange, or red).

The pattern works like this:

OpenValve blinks a certain number of times, then makes a clear pause, then repeats the same pattern. To read the value, count the blinks between two pauses.

For example, if the current soil moisture value is **4**, the LED pattern looks like this:

```text
blink, blink, blink, blink, pause
blink, blink, blink, blink, pause
blink, blink, blink, blink, pause
```

This means the value is **4**.

In practice, you simply count the blinks in your head:

```text
1, 2, 3, 4 ..... 
1, 2, 3, 4 ..... 
1, 2, 3, 4 ..... 
```


### Learn all about the UI

To get familiar with the UI, there are two options:

1. **[Interactive Manual](./interactive-manual)**:  A virtual OpenValve that lives in your browser and behaves just like the real device.
2. **[Classic Manual](./classic_manual/classic-manual)**: It provides detailed information about every available UI state, how to access them, how to interpret the LEDs, and which settings can be changed.

