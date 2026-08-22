---
title: Pressurized setup
sidebar_position: 1
---

# Pressurized setup (> 0.5 bar / > 7 psi)

A pressurized setup means that OpenValve is connected to a water source such as a **garden tap, pressurized water line, or pump**, where the water pressure typically exceeds 0.5 bar.

OpenValve can operate at pressures up to **4 bar (60 psi)**. This limit must not be exceeded at any time, including when OpenValve is closed and the water pressure is static.

## Do I need a pressure regulator?

A pressure regulator reduces the water pressure in your irrigation system. Whether you need one mainly depends on the pressure of your water source, but also on the pressure ratings of the other components in your setup, such as hoses, fittings, and emitters.

### Up to 2 bar

If your water source does not exceed **2 bar**, a pressure regulator is usually not required.

However, always make sure that all hoses, fittings, and emitters in your irrigation system are rated for the available pressure.

### Between 2 and 4 bar

OpenValve can operate directly at pressures between **2 and 4 bar**. Whether a regulator is required depends on the pressure rating of the complete irrigation system rather than OpenValve itself.

For example, if you use a drip hose that is rated for 4 bar and all hoses, pipes, fittings, and connectors in the system are also rated for at least 4 bar, no pressure regulator is required and OpenValve can be connected directly to the water source.

If you use micro-irrigation components such as small 4/6 mm tubing, drippers, or micro-sprinklers, a pressure regulator is more likely to be required. These components commonly operate at pressures below 2 bar.

In this case, a typical inexpensive **irrigation pressure regulator** can be used. These regulators reduce the pressure while water is flowing and usually operate within a specified flow-rate range, protecting downstream irrigation components from excessive operating pressure.

### Above 4 bar

If your water source can exceed **4 bar at any time**, a **static pressure-reducing valve**, such as a house pressure regulator, is required upstream of OpenValve.

Unlike a typical irrigation pressure regulator, a house pressure regulator also reliably limits the pressure when no water is flowing. It should be set to a suitable irrigation pressure below 4 bar.

When a house pressure regulator is used, an additional irrigation pressure regulator is **not required**.

:::warning

The pressure at OpenValve must never exceed **4 bar (60 psi)**.

If your water source can exceed this pressure, do not rely on a typical irrigation pressure regulator. Use a pressure-reducing valve that also limits the pressure when the water is static.

:::

## Example Installation

Here is an example of how OpenValve can be installed in a pressurized irrigation system.

```text
garden tap
  ↓
Pressure regulator, if required:
  - Irrigation pressure regulator if required by the irrigation components (typically between 2–4 bar)
  - House pressure regulator if the water source can exceed 4 bar
  ↓
3/4" thread to 1/2" hose compression fitting
  ↓
1/2" hose
  ↓
1/2" hose to 1/2" thread compression fitting
  ↓
OpenValve
  ↓
1/2" hose to 1/2" thread compression fitting
  ↓
1/2" hose
  ↓
1/2" to 1/2" hose adapter
  ↓
1/2" drip hose
```