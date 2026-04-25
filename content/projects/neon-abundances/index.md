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

The interactive plot below reproduces the *Cloudy* photoionization models from our 2021 publication. It compares the internal gas structure of a cloud ionized by an AGN (red solid line, hard X-ray power-law) versus a star-forming H <span style="font-variant: small-caps;">ii</span> region (blue dashed line, stellar SED) across a normalized radius ($R/R_{\rm e}$). 

Because the axes are normalized to the total radius of the cloud ($R_{\rm e}$), the physical differences between a Strömgren sphere (H <span style="font-variant: small-caps;">ii</span>) and an extended Partially Ionized Zone (AGN) become starkly apparent:

* **Top Panel (Ne²⁺/Ne):** The AGN model actually achieves a higher initial ionization fraction near the illuminated face compared to the stellar model. However, because the AGN's total volume is dominated by a massive Partially Ionized Zone (PIZ), the highly ionized Ne²⁺ fraction drops off rapidly on the normalized scale, physically crossing the H <span style="font-variant: small-caps;">ii</span> line at $R/R_{\rm e} \approx 0.55$. 
* **Middle Panel (O²⁺/O):** The H <span style="font-variant: small-caps;">ii</span> region exhibits the classic behavior of a Strömgren sphere: the highly ionized species fill nearly the entire volume, creating a flat plateau until the sharp boundary drop-off at $R_{\rm e}$. Conversely, the AGN model exhibits a convex decay, with O²⁺ squashed into the inner region.
* **Bottom Panel (Electron Temperature, $T_{\rm e}$):** This panel reveals the most critical physical distinction. The AGN temperature starts high at the illuminated face, dips rapidly around $R/R_{\rm e} \approx 0.1$ (where O²⁺ and Ne²⁺ cooling is highly efficient), and then spikes dramatically. It remains extremely hot ($\sim 1.5 \times 10^4$ K) across the remaining 80% of the radius because the deeply penetrating X-rays continue to heat the PIZ where line-cooling is inefficient. The H <span style="font-variant: small-caps;">ii</span> region, lacking hard X-rays, maintains a relatively flat, cooler temperature profile.

*(Hover over the curves to see the exact fractional abundances and temperatures at any given depth).*

<iframe src="/simulations/Nebular_Structure_Profiles.html" width="100%" height="830px" style="border:none; border-radius: 12px;"></iframe>
