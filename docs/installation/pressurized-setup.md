---
title: Pressurized setup
sidebar_position: 1
---
# Pressurized setup (> 0.5 bar / > 7 psi)

A pressurized setup in this context means that OpenValve is connected to a water source such as a garden tap/outdoor faucet that has a static pressure exceeding 0.5 bar.

OpenValve is rated for a maximum operating pressure of **4 bar**. During normal operation, the pressure at OpenValve must not exceed this value. If your water source provides more than 4 bar, a house pressure regulator is required. When the pressure is below 4 bar but still above 2 bar (as is common in most pressurized lines), an irrigation pressure regulator is strongly recommended for drip or micro-irrigation systems, because many irrigation components are not designed for high pressure. A pressure regulator can also improve battery life by reducing the force needed to close the valve. Always connect pressure regulators upstream (before OpenValve).

:::warning

Pressure reducers should always be installed upstream (before OpenValve, not after).

:::

Be careful when choosing an pressure regulator. There are two types of pressure regulators:

- irrigation pressure regulators
- house pressure regulators

Irrigation pressure regulators are usually designed as **downstream regulators**. They reduce the pressure **only within a specified flow rate**, but they do not reduce the pressure reliably or at all when the valve is closed and the pressure is static. When the water source does not exceed 4 bar, a standard irrigation pressure regulator is enough. However when the water source pressure is above 4 bar, a house pressure regulator is required. 

:::tip

House pressure regulators also limit the pressure reliably when the water pressure is static (no water is flowing).

:::

Here is an example of how OpenValve can be installed in a pressurized system.

```text
Faucet
  ↓
Irrigation pressure regulator (if pressure > 2 bar) / House pressure regulator (if pressure > 4 bar)
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