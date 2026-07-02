# Literature Map: Lagrangian / Free-Drifting Wave-Follower Buoys

*Compiled 2026-07-01 · 170 core papers (2018–2026), harvested from Crossref and enriched via OpenAlex.*

## Scope

This map covers the subfield around **free-drifting, wave-following buoy platforms** — instruments that move with the water surface in a Lagrangian frame to measure ocean waves, currents, and drift, in contrast to moored/anchored wave buoys. It sits at the intersection of low-cost open-source oceanographic instrumentation (Sofar Spotter, SWIFT/microSWIFT, OpenMetBuoy), GNSS/IMU wave sensing, and surface-drifter oceanography. A search across 18 query phrases returned 484 candidate works; after relevance filtering 219 were on-topic, of which **170** form the core (an adjacent cluster of 23 wave-energy-converter "oscillating buoy" papers was set aside as peripheral).

## The shape of the field

Two figures accompany this report:

- **fig1_themes_over_time.png** — annual output by theme. Output roughly doubled from ~10–13 papers/yr (2018–2020) to ~23–24/yr (2021–2025). *Wave measurement methodology* is the dominant thread (n=87), followed by *drift/transport/trajectory* (n=31) and *platform & sensor hardware* (n=26).
- **fig2_top_cited.png** — the most-cited works, colour-coded by theme.

## The six themes

### 1. Wave measurement methodology (n=87) — the core engine of the field
How to turn a freely-moving platform's motion into a wave spectrum. Key sub-threads: directional spectrum estimation, heave/motion correction, the **wave-buoy analogy** (inferring sea state from vessel or buoy response), and increasingly machine-learning spectral inference.
- [Eulerian–Lagrangian simulation of wave-induced microplastic dispersion in nearshore zones: Processes and implications](https://doi.org/10.1016/j.ecss.2025.109626) — Rahmani, Stocchino, *Estuarine, Coastal and Shelf Science* (2026), 2 citations
- [Wave estimation solution based on wave buoy analogy: Development and application to in-service ship operational data](https://doi.org/10.1016/j.oceaneng.2026.126694) — Lee, Park et al., *Ocean Engineering* (2026), 0 citations
- [Arctic deployment of a fully integrated self-powered drifting buoy harvesting wave energy via a triboelectric nanogenerator](https://doi.org/10.1016/j.nanoen.2026.111830) — Lu, Jung et al., *Nano Energy* (2026), 0 citations
- [Research on wave buoy calibration using the vertical lifting method of a linear motor](https://doi.org/10.1088/1361-6501/ae3595) — Huang, Zhai et al., *Measurement Science and Technology* (2026), 0 citations
- [Optimization and parameter influence analysis of heave plate OWC wave energy buoy under broadband wave conditions](https://doi.org/10.1016/j.energy.2026.141667) — Zhang, Ren et al., *Energy* (2026), 0 citations

### 2. Drift, transport & trajectory (n=31)
Using drifters to measure surface currents, Stokes drift, dispersion, and convergence — plus operational uses (search-and-rescue, debris/microplastic tracking). This is where the "Lagrangian" identity is strongest.
- [Short-Term Drifter Position Estimation Based on Ship-Generated Waves for Search and Rescue](https://doi.org/10.26748/ksoe.2025.048) — Zhao, Kang et al., *Journal of Ocean Engineering and Technol* (2026), 0 citations
- [Modeling the convergence of buoyant debris in the Indian Ocean: Insights from surface drifter trajectories and Lagrangian simulations](https://doi.org/10.1016/j.marpolbul.2026.119732) — Chauchadis, Maes et al., *Marine Pollution Bulletin* (2026), 0 citations
- [Estimation and Analysis of Stokes Drift Based on CFOSAT Wave Spectrum Data](https://doi.org/10.3390/rs18040574) — Duan, Song, *Remote Sensing* (2026), 0 citations
- [Stokes Drift and Wind Drift in a Rotating Equilibrium Sea](https://doi.org/10.1175/jpo-d-25-0198.1) — Samelson, Zippel, *Journal of Physical Oceanography* (2026), 0 citations
- [Simulation of the wave-induced Stokes drift effect under typhoon conditions using FVCOM: Impacts on the upper ocean temperature](https://doi.org/10.1088/1742-6596/3178/1/012004) — Wang, Han et al., *Journal of Physics: Conference Series* (2026), 0 citations

### 3. Platform & sensor hardware (n=26)
Buoy design, GNSS/IMU integration, energy harvesting, and — directly relevant to your work — **open-source / low-cost** platforms (OpenMetBuoy, economical drifter designs, teaching platforms like MIT's Drifter Challenge).
- [Heave added mass coefficient of a spherical buoy](https://doi.org/10.1007/s10665-026-10523-5) — Usman, Behera et al., *Journal of Engineering Mathematics* (2026), 0 citations
- [Drifter Challenge: A Low-Cost, Hands-On Platform for Teaching Ocean Instrumentation and Sensing](https://doi.org/10.5670/oceanog.2025.e312) — Massachusetts Institute of Technology, Xia et al., *Oceanography* (2025), 1 citations
- [Lagrangian dispersion in the Red River plume region, Northeast Vietnam, from drifter observations and modeling](https://doi.org/10.1016/j.jmarsys.2025.104143) — Sentchev, Nguyen-Duc et al., *Journal of Marine Systems* (2025), 0 citations
- [Lagrangian characterization of the southwestern Atlantic from a dense surface drifter deployment](https://doi.org/10.1016/j.dsr.2024.104319) — Saraceno, Bodnariuk et al., *Deep Sea Research Part I: Oceanographic * (2024), 13 citations
- [Real-Time and Long-Term Monitoring of Coastal Water Turbidity Using an Ocean Buoy Equipped with an ADCP](https://doi.org/10.3390/s24216979) — Bian, Huang, *Sensors* (2024), 8 citations

### 4. Validation & intercomparison (n=16)
Benchmarking drifting buoys against moored buoys, satellite altimetry, and model hindcasts; calibration methods and uncertainty budgets.
- [Rogue wave indicators from global models and buoy data](https://doi.org/10.5194/os-22-367-2026) — Azevedo, Marcon et al., *Ocean Science* (2026), 1 citations
- [Comparative analysis of hindcast data against wave buoy measurement for a site in the mediterranean sea](https://doi.org/10.1080/17445302.2026.2658742) — Ameer, Lo Re et al., *Ships and Offshore Structures* (2026), 0 citations
- [Evaluation of Measurement Uncertainty for the Wave Buoy Calibration Device Using a Vertical Lifting Method](https://doi.org/10.3390/jmse13030605) — Huang, Zhao et al., *Journal of Marine Science and Engineerin* (2025), 0 citations
- [Ensemble-based data assimilation of significant wave height from Sofar Spotters and satellite altimeters with a global operational wave model](https://doi.org/10.1016/j.ocemod.2023.102200) — Houghton, Penny et al., *Ocean Modelling* (2023), 17 citations

### 5. Field campaigns & observations (n=5)
Deployments in demanding settings — sea ice/polar, typhoons, submesoscale fronts — that report wave/sea-state data as the primary product.
- [Numerical Simulation of Regular Wave and Ice Floe Interaction Using Coupled Eulerian–Lagrangian Method](https://doi.org/10.3390/w17131879) — Yu, Tian, *Water* (2025), 2 citations
- [IMPACT OF DATA ASSIMILATION FOR TYPHOON-GENERATED EXTREME WAVE BASED ON DRIFTING WAVE BUOY OBSERVATION](https://doi.org/10.9753/icce.v38.waves.55) — Yamasaki, Shimura et al., *Coastal Engineering Proceedings* (2025), 0 citations
- [Drifter Deployment Strategies to Determine Lagrangian Surface Convergence in Submesoscale Flows](https://doi.org/10.1175/jtech-d-22-0129.1) — Aravind, Huntley et al., *Journal of Atmospheric and Oceanic Techn* (2024), 3 citations
- [A comparison of an operational wave–ice model product and drifting wave buoy observation in the central Arctic Ocean: investigating the effect of sea-ice forcing in thin ice cover](https://doi.org/10.33265/polar.v42.8874) — Nose, Rabault et al., *Polar Research* (2023), 9 citations

### 6. Air-sea interaction & remote sensing (n=5)
Buoy-based observation of momentum flux, Langmuir turbulence, and Stokes-drift coupling; cross-validation with SAR/radar surface-current retrievals.
- [Comprehensive Assessment of Ocean Surface Current Retrievals Using SAR Doppler Shift and Drifting Buoy Observations](https://doi.org/10.3390/rs17122007) — Fan, Zhang et al., *Remote Sensing* (2025), 5 citations
- [Characterizing wind, wave, and Stokes drift interactions in the upper ocean during Typhoon Doksuri using the COAWST model](https://doi.org/10.3389/fmars.2025.1524724) — Han, Zuo et al., *Frontiers in Marine Science* (2025), 4 citations
- [Footprint of the air-sea momentum transfer saturation observed by ocean wave buoy network in extreme tropical cyclones](https://doi.org/10.1016/j.coastaleng.2024.104537) — Shimura, Mori et al., *Coastal Engineering* (2024), 10 citations
- [Wind speed and direction estimation from wave spectra using deep learning](https://doi.org/10.5194/amt-15-1-2022) — Jiang, *Atmospheric Measurement Techniques* (2022), 17 citations

## Reference platforms cited across the literature

| Platform | Character | Anchor reference |
|---|---|---|
| **Sofar Spotter** | Commercial low-cost solar GNSS wave buoy; now the most-cited single instrument in the set | Raghukumar et al. 2019 (84c) |
| **SWIFT / microSWIFT** | UW-APL free-drifting wave/turbulence float; open designs | Thomson et al. 2018 (52c) |
| **OpenMetBuoy (OMB)** | Open-source, low-cost met-ocean drifter (Rabault et al.) | 2025 OMB-v2021 in-situ analysis |
| **Open-source drifter designs** | Economical lake/coastal drifters; teaching kits (MIT Drifter Challenge) | 2024–2025 |

## Where the frontier is (2024–2026)

The most recent work concentrates in three places, all relevant to a Lagrangian wave-follower project:
1. **Open hardware maturing into a data ecosystem** — the OpenMetBuoy-v2021 in-situ + trajectory-simulation analyses, economical open-source drifter designs, and education-oriented kits signal that the low-cost/open lane is now producing reusable datasets, not just prototypes.
2. **Machine learning for inference** — physics-informed neural networks reconstructing surface velocity from drifter data; deep-learning wave/wind spectrum estimation; ML-conditioned sea-state estimation.
3. **Fusion & assimilation** — combining drifter observations with numerical models and satellite (CFOSAT, SAR Doppler) for currents, Stokes drift, and extreme-wave nowcasting.

## Gaps / opportunities visible in the map

- **Directional-spreading validation for low-cost buoys is thin** — only a handful of recent Spotter-vs-reference directional-spreading comparisons; free-drifting platforms complicate the classic moored-buoy directional methods.
- **Eulerian-vs-Lagrangian sampling bias** on wave spectra is discussed but not systematically quantified for the newer cheap platforms — a natural methods contribution.
- **Cross-platform interoperability / open data standards** are emerging but not consolidated; OMB, SWIFT, and Spotter ecosystems remain largely separate.

## Data & method notes

- Discovery: Crossref bibliographic search across 18 phrase queries, journal-articles only, from 2018. Abstracts back-filled from OpenAlex where Crossref lacked them.
- Relevance: rule-based keyword scoring (wave-term × platform-term co-occurrence, plus strong-signal terms), then a per-paper LLM classification into the six themes + adjacent/off-topic.
- Citation counts are the max of Crossref and OpenAlex and reflect the harvest date; they undercount very recent (2025–2026) papers.
- 2026 counts are partial (indexed-to-date).
- Full record list with DOIs: **lagrangian_wave_buoy_literature.csv**.
