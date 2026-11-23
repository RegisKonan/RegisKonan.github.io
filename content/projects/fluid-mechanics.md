---
title: "Saltwater Intrusion in Anisotropic Porous Media"
summary: "Numerical study of how direction-dependent permeability affects the advance of the freshwater–saltwater interface (salt wedge) in aquifers. UFHB Master's thesis in Fluid Mechanics."
tags:
  - Fluid Mechanics
  - Porous Media
  - Numerical Simulation
date: 2020-02-28
image:
  filename: project-saltwedge.jpg
  caption: "Advance of the salt wedge under pumping without recharge (FreeFem++ simulation). Red: salt water, blue: fresh water."
  focal_point: Center
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/RegisKonan/UFHB_master_Fluid_mechanics
---

## Motivation

Fresh water makes up less than 3% of the water on Earth, and much of it is stored underground. In coastal aquifers, salt water can push into fresh groundwater, forming a **salt wedge** that threatens drinking-water supplies.

## Question

Most classical salt-wedge results assume an **isotropic** medium, where permeability is the same in every direction. Real soils are often **anisotropic**. This thesis asks: **how does anisotropic permeability change the position and advance of the freshwater–saltwater interface?**

## Model and method

Groundwater flow in a 2D vertical section $(x, z)$ of an unconfined aquifer is modelled with a storage equation coupled with Darcy's law, plus transmission conditions at the freshwater–saltwater interface $\Sigma$:

$$
S\,\frac{\partial h}{\partial t} + \operatorname{div}(\mathbf{U}) = Q^A - Q^P,
\qquad
\mathbf{U} = -\mathbf{K}\,\nabla h ,
$$

where $h$ is the hydraulic head, $S$ the storage coefficient, and $Q^A$ and $Q^P$ the recharge and pumping rates. Anisotropy enters through the conductivity tensor

$$
\mathbf{K} = \begin{pmatrix} K_{xx} & 0 \\ 0 & K_{zz} \end{pmatrix}, \qquad K_{xx} = 10\,K_{zz},
$$

since horizontal permeability is typically larger than vertical permeability.

The model was solved with the **finite element method in FreeFem++** on a 4 m × 2 m aquifer, simulated over **1,300 days** in two scenarios: **pumping without recharge** and **pumping with recharge**.

## Results

- **Without recharge:** the salt wedge advances strongly between days 500 and 700 and loses its oblique shape. From **day 1,000**, a cone of salt water rises towards the well (*upconing*). By day 1,300 it approaches the critical point beyond which the aquifer becomes unusable for drinking water.
- **With recharge:** the wedge advances much more slowly, and the saltwater cone only appears at **day 1,300**, about **300 days later** than without recharge.
- **Takeaway:** recharge (e.g. from rainfall) delays saltwater intrusion, but on its own it is only marginally sufficient to limit the risk under excessive pumping.

## Resources

- 📄 [Full thesis (PDF, in French)](https://github.com/RegisKonan/UFHB_master_Fluid_mechanics/blob/main/Memoire_Djaha_Regis.pdf): *Influence of permeability anisotropy on the advance of the freshwater–saltwater interface*
- 💻 [Repository](https://github.com/RegisKonan/UFHB_master_Fluid_mechanics)

*Master's in Mechanics and Energetics, Fluid and Interactive Phenomena track — Université Félix Houphouët-Boigny, Côte d'Ivoire.*
