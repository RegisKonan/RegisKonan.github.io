---
title: "Darcy's Law in a 2D Porous Embankment"
summary: "Analytical and numerical study of seepage through horizontal, multilayer and inclined embankments, to quantify how much water an embankment lets through. AIMS Rwanda Master's thesis."
tags:
  - Applied Mathematics
  - Porous Media
  - Fluid Mechanics
date: 2022-06-28
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/RegisKonan/AIMS_master_embankment
---

## Motivation

Embankments store and channel fresh water, but some water always seeps through them. Knowing **how much** is key to balancing water conservation against flood risk.

## Model

Flow through the porous embankment is described by **Darcy's law**:

$$
\mathbf{U} = -\frac{K}{\mu}\left(\nabla p - \rho \mathbf{g}\right),
$$

where $K$ is the permeability, $\mu$ the dynamic viscosity, $p$ the pressure and $\rho$ the fluid density. For a horizontal embankment of length $L$ separating two water tables of heights $y_0$ and $y_1$, the steady discharge per unit width is

$$
Q = \frac{K g \left(y_0^2 - y_1^2\right)}{2 \nu L},
$$

with $\nu$ the kinematic viscosity. The analysis is then extended to **multilayer embankments** (layers of different permeability) and **inclined embankments**, where gravity acts along the slope.

## Results

- Discharge grows **linearly with permeability** and decreases with embankment length.
- **Steeper slopes increase** the flow.
- Combining materials of different permeability changes both the total discharge and how water is distributed inside the embankment.
- Case study (earthfill embankment on impermeable bedrock, two layers): computed discharge $Q \approx 2.68 \times 10^{-3}\ \mathrm{m^2/s}$, consistent with the theoretical prediction.

## Resources

- 📄 [Full thesis (PDF)](https://github.com/RegisKonan/AIMS_master_embankment/blob/main/Essay_phase_regis_konan.pdf)
- 💻 [Repository](https://github.com/RegisKonan/AIMS_master_embankment)
