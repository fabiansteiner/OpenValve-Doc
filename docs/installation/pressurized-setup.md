---
title: Pressurized setup
sidebar_position: 1
---
# Pressurized setup (> 0.5 bar / > 7 psi)

A pressurized setup in this context means that OpenValve is connected to a water source such as a garden tap/outdoor faucet that has a static pressure exceeding 0.5 bar.

OpenValve is rated for a maximum operating pressure of **2 bar**. This means that the pressure applied to OpenValve should not exceed 2 bar during normal operation. If your water source provides more than 2 bar, a pressure reducer is required before OpenValve.

:::warning

Be careful when choosing a pressure reducer.

:::

Many pressure reducers for irrigation are designed as **downstream pressure reducers**. They reduce the pressure only within a specified flow rate, but they may not reduce the pressure reliably or at all when the valve is closed and the pressure is static. 

:::info

List of compatibe pressure reducers is in work

:::

Here is an example of how OpenValve can be installed in a pressurized system.

```text
Faucet
  ↓
Pressure reducer (if pressure > 2 bar)
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
1/2" to 1/2" adapter
  ↓
1/2" drip hose
```