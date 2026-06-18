---
title: First Setup
sidebar_position: 6
description: "Recommended process for setting up OpenValve for the first time."
---
# First Setup

After OpenValve is installed, the first setup should be done step by step. The goal is not to find the perfect settings immediately, but to establish a setup where the sensor can reliably detect the effects of irrigation. Once this foundation is in place, the other settings can be refined over time.

:::tip

The general rule is: Choose the sensor placement first. Then adjust Opening Threshold and Additional Time based on how OpenValve behaves in that exact setup.

:::
## Step-by-step

Before starting, make sure that:

* the water supply is turned off for now
* Opening Threshold is set to **1** (factory setting)
* Additional Time is set to **1** (factory setting)

These are the recommended steps for the first setup:

1. **Place the sensor**

   [Place the sensor in a representative spot](./how-openvalve-waters/sensor-placement.md) where you want OpenValve to control the soil moisture. The sensor should be inside or close to the plant root zone and must have good contact with the surrounding soil. Bury the sensor completely, including the housing, so that only the cable remains above the soil surface.
2. **Check that the valve is closed**

   After sensor placement press the button on OpenValve to wake it up. If the sensor was placed correctly and the soil surrounding the sensor is not extremely dry, OpenValve should now (if it did not already do so automatically) close the valve.
3. **Turn on the water supply**

   Once OpenValve is closed (blue LED OFF), turn on the water supply by opening the outdoor faucet or water container. Starting with the valve closed prevents the system from watering immediately and allows you to safely pressurize the setup. While doing so, inspect all hoses, fittings, and connections for leaks.
4. **Test the irrigation system**

   [Open the valve manually](./user_interface/classic_manual/manually-open.md) and check if OpenValve opens properly and whether water reaches all intended irrigation points. Pay particular attention to the emitters at the end of the line, as these are often the first to reveal problems with insufficient flow or uneven distribution. If you are using adjustable emitters, this is also a good opportunity to roughly set their flow rates according to the needs of the individual plants.
5. **Wait until soil is dry**

   Wait until the soil reaches the moisture level where you would normally water your plants. Depending on the weather and the current soil moisture, this may be the case immediately or take several days.
6. **Check  current soil moisture value**

   When the soil is dry enough (based on your own judgement), wake OpenValve and read the current soil moisture value using the LEDs. This value is a good starting point for the Opening Threshold.
7. **Set the Opening Threshold**

   Set the [Opening Threshold](./how-openvalve-waters/opening-threshold.md) to the current soil moisture value. This tells OpenValve: “When the soil gets this dry, start watering.” As soon as you set the Opening Threshold to the current soil moisture value, the valve will open immediately.
8. **Let OpenValve perform a watering cycle**

    Let OpenValve water and observe what happens. Use your phone or a timer to measure how long OpenValve stays open. This gives you a feeling for how long it takes until water reaches the sensor in your setup.
9. **Adjust Additional Time if needed**

   If the watering time is too short, increase the [Additional Time setting](./how-openvalve-waters/additional-time.md). This gives the water more time to move deeper or spread farther through the soil in the next watering cycle.
10. **Observe the first week**

    Keep an eye on the watering behaviour during the first few cycles. If the plants need water more often, increase the Opening Threshold. If you want the soil to dry out more before watering, decrease the Opening Threshold. If watering should be longer or shorter per cycle, adjust Additional Time. If you use adjustable emitters, you can also fine-tune the amount of water at each plant. Be careful however when adjusting the emitter next to the sensor, as this will probably also change if and how long it takes until water reaches the sensor.

:::info

If changing Opening Threshold, Additional Time, and emitter flow does not lead to a satisfying result, the sensor most likely needs a different placement.

:::