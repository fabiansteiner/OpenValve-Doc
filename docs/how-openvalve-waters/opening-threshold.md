---
title: Opening Threshold
sidebar_position: 2
description: "Learn how the Opening Treshold setting affects watering."
---


# Opening Threshold

The Opening Threshold is a device setting that defines how dry the soil must become before OpenValve starts watering.

The setting can be changed from **1** to **8**:

* **1** means the soil must become very dry before OpenValve opens.
* **8** means OpenValve opens while the soil is still quite moist.

A low value lets the soil dry out more before watering.
A high value waters earlier and keeps the soil wetter.

The value is based on the soil moisture measured by the sensor. Each Opening Threshold value corresponds to an approximate volumetric water content:

| Opening Threshold | Volumetric water content |
| ----------------: | -------------------------------: |
|                 1 |                              12% |
|                 2 |                              16% |
|                 3 |                              20% |
|                 4 |                              24% |
|                 5 |                              28% |
|                 6 |                              32% |
|                 7 |                              36% |
|                 8 |                              40% |

For example, if the Opening Threshold is set to **4**, OpenValve starts watering when the measured soil moisture drops to about **24%** or below.

The correct value for a setup depends on the plants that should be watered, the soil type, the sensor placement, and the overall setup environment. For that reason, there is no universal correct value. For example, there is no rule like “use threshold 4 for tomatoes”.

Once the soil becomes dry enough, OpenValve opens. But [when does it close?](./additional-time)
