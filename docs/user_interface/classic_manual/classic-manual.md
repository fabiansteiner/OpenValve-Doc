---
title: Classic Manual
sidebar_position: 3
description: "Get familiar with the User Interface using the classic manual"
---

This Flow Diagram gives you an overview of which states exist, how to move between them and how to interpret the LEDs.

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="flow diagram" label="Flow Diagram" default>
    ![User Interface State and Flow Diagram](/img/UIFlowDiagramV7.svg)
  </TabItem>
  <TabItem value="States" label="States">
    ![User Interface State and Flow Diagram](/img/UIFlowDiagramStatesV7.svg)
  </TabItem>
  <TabItem value="Transitions" label="Transitions">
    ![User Interface State and Flow Diagram](/img/UIFlowDiagramTransitionsV7.svg)
  </TabItem>
</Tabs>








:::tip

"The beginning is the end. And the end is the beginning." - Dark

You may have to move forward first to "return" to a state.

:::

Here is a list of all possible states:

| State | Description |
| ----------- | ------------------ |
| [Sleep](./sleep)       |       In sleep mode OpenValve waters following the user settings.  |
| [Display Battery Level](./display-battery-level)       |                The upper LED indicates the battery level. |
| [Display Current Soil Moisture](./display-current-soil-moisture)       |               The upper LED indicates the current soil moisture by the number of green LED blinks. |
| [Manually Open](./manually-open)      |               This state allows immediate irrigation, independent of current soil moisture readings. |
| [Select Opening Threshold](./select-opening-threshold)       |               Choose whether to adjust the opening threshold or the additional time setting. |
| [Select Additional Time](./select-additional-time)       |               Choose whether to adjust the opening threshold or the additional time setting. |
| [Change Opening Threshold](./change-opening-threshold)        |               In this state the opening threshold setting can be changed. The current setting is shown by the number of green LED blinks (1–8)|
| [Change Additional Time](./change-additional-time)       |               In this state the additional time setting can be changed. The current setting is shown by the number of orange LED blinks (1–5)|
| [Off](./off)       |                Switching to this state turns off OpenValve completely and closes the valve. |

