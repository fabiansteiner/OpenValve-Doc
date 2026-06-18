---
title: Sensor Placement
sidebar_position: 4
description: "Learn the about the importance of a well placed sensor."
---
# Sensor Placement

:::tip

**Sensor placement is the foundation of the whole setup.** Good device settings cannot compensate for a bad sensor position.

:::

Capacitive soil moisture sensors do not measure the whole pot, bed, or field. They mainly measure the soil close to the sensor blade. In practice, this measurement range often extends only about 1-5 cm from the blade, depending on the sensor. The soil directly touching the sensor has the strongest influence on the reading.

<img src="/img/Sensor_MeasurementVolume.png" alt="visualization of sensors measurement volume" title="visualization of sensors measurement volume" width="350"/>

The important takeaway is:

**The sensor gives a local wet/dry reading.**
It does not represent the moisture condition of the entire pot, bed, or field.

The sensor must be placed in a representative spot with good soil contact. Avoid placing the sensor directly next to:

* stones
* thick roots
* air pockets
* the wall of a pot/bed


### Sensor depth
:::warning

Sensor depth influences both when OpenValve opens and how long it waters.

:::

**The sensor must be buried completely**, including the black housing. Only the cable should stick out of the soil. This helps the sensor stay in the same position over time and prevents the reading from being influenced by accidental touches or slight pulling on the cable.

A sensor close to the surface usually makes OpenValve open sooner, because the top layer of soil dries out first.

A deeper sensor usually stays moist for longer, so OpenValve opens later. At the same time, a deeper sensor often increases the watering time, because it takes longer until water reaches it.

Place the sensor inside or close to the root zone of your plants, at the depth where you actually want to control the moisture. For shallow-rooted plants, this may be closer to the surface. For deeper-rooted plants, the sensor may need to be placed deeper.

### Make sure water reaches the sensor

OpenValve must be able to detect that watering is working.

If irrigation water never reaches the sensor, OpenValve cannot see the moisture increase and would keep the valve open for too long.

As a safety measure, OpenValve automatically closes the valve if no increase in soil moisture is detected after **90 minutes**.

If this happens, check whether:

* the sensor is placed where irrigation water never reaches
* the water source is turned on
* the container is empty
* the hose or emitter is blocked


For OpenValve to behave consistently, water should enter the soil at repeatable spots and reach the sensor in a similar way every time.

For that reason, **drip irrigation is recommended.** A sprinkler with strong, clearly defined water streams can also work but fine mist or spray irrigation is less reliable, especially outdoors. Wind can carry the water away, so the area around the sensor may stay dry even though watering is happening. This can lead to inconsistent and non-repeatable watering behaviour.