---
title: "Direct Abundance Determination of Neon"
summary: "Utilizing a combination of optical and infrared emission lines to derive highly accurate, direct gas-phase neon abundances in Seyfert 2 galaxies."
tags:
  - Seyfert Galaxies
  - Infrared Astronomy
  - Extragalactic Astrophysics
date: "2021-09-16T00:00:00Z"
math: true
---
**[Read the full published paper here](https://doi.org/10.1093/mnras/stab2610)**

This research bridges the gap between optical and infrared observational datasets. By leveraging multi-wavelength emission lines, this project bypasses traditional temperature-dependent optical limitations, allowing for a more robust and direct measurement of Neon abundances within the complex environments of Seyfert 2 AGNs.

### Interactive Neon Abundance Simulator
*Explore the temperature dependence of optical derivations versus infrared derivations.*

<iframe src="/simulations/Neon_Simulator.html" width="100%" height="550px" style="border:none; border-radius: 12px;"></iframe>

### Interactive Figure 5: Nebular Structure Profiles

The interactive plot below reproduces the <span style="font-variant: small-caps;">cloudy</span> photoionization models from our 2021 publication. It compares the internal gas structure of a cloud ionized by an AGN (red solid line, hard X-ray power-law) versus a star-forming H <span style="font-variant: small-caps;">ii</span> region (blue dashed line, stellar SED) across a normalized radius ($R/R_{\rm e}$). 

Because the axes are normalized to the total radius of the cloud ($R_{\rm e}$), the physical differences between a Strömgren sphere (H <span style="font-variant: small-caps;">ii</span>) and an extended Partially Ionized Zone (AGN) become starkly apparent. By plotting the fractional abundances and electron temperature, this figure demonstrates exactly why traditional H <span style="font-variant: small-caps;">ii</span> region assumptions fail when applied to AGNs:

* **Bottom Panel (Electron Temperature, $T_{\rm e}$):** The AGN model exhibits a very distinct temperature distribution compared to the H <span style="font-variant: small-caps;">ii</span> region, showing a stronger decrease with the radius.
* **Middle & Top Panels (O²⁺/O and Ne²⁺/Ne):** In the H <span style="font-variant: small-caps;">ii</span> region model, both ionic ratios show similar distributions along the radius, confirming the standard assumption that $T_{\rm e}$(O <span style="font-variant: small-caps;">iii</span>) $\approx$ $T_{\rm e}$(Ne <span style="font-variant: small-caps;">iii</span>). In the AGN model, however, the Ne²⁺/Ne ionic abundance extends significantly further into the outer nebular radius (where the temperature is lower) in comparison to the O²⁺/O abundance. While O²⁺ drops off rapidly, Ne²⁺ persists throughout the cooler regions of the cloud.
* **The Critical AGN Deviation:** In the AGN model, the Ne²⁺/Ne ionic abundance extends to an outer nebular radius (where the temperature is lower) in comparison to the O²⁺/O abundance. Because Ne²⁺ exists in a distinct, cooler outer region compared to O²⁺, the assumption that $T_{\rm e}$(O <span style="font-variant: small-caps;">iii</span>) $\approx$ $T_{\rm e}$(Ne <span style="font-variant: small-caps;">iii</span>) is strictly invalid for AGNs. Furthermore, this structural difference clearly indicates that the standard assumption used in H <span style="font-variant: small-caps;">ii</span> regions, (Ne²⁺/O²⁺) = (Ne/O), cannot be applied to AGNs.

<iframe src="/simulations/Nebular_Structure_Profiles.html" width="100%" height="830px" style="border:none; border-radius: 12px;"></iframe>
