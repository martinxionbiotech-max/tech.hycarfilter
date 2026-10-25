# Cabin Filter Key Parameters

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data cabin filter category](https://data.hycarfilter.com/products/cabin-filter/).

The cabin filter (cabin air filter) protects **people** rather than machines — it filters the air entering the cabin from outside the vehicle. The evaluation criteria therefore shift from "protecting the engine" to "protecting occupant health and comfort," and the parameter logic differs from other categories.

## I. Parameter list

| Parameter | Definition | Same value on this site (data) |
|---|---|---|
| Particle filtration efficiency | Interception rate of particulates (pollen/dust/PM) | `hy-cf-particle` >=95% · `hy-cf-carbon` >=96% · `hy-cf-hepa` >=99.97% (H13) |
| Gas adsorption | Activated carbon adsorption of VOC/odor/exhaust | `hy-cf-carbon`/`hy-cf-hepa` contain an activated carbon layer |
| Airflow / differential pressure | Cabin air supply restriction | Data is subject to the data site (low differential pressure preferred) |
| Outer dimensions | Length × width × height | `hy-cf-*` all 240×200×30 mm |

## II. Positioning of the three tiers

**[Industry Knowledge]**

- **Particle type** (`hy-cf-particle` >=95%): base model, intercepts pollen/large particle dust;
- **Activated carbon type** (`hy-cf-carbon` >=96%): particles + activated carbon, covering odor/VOC adsorption, mainstream for urban commuting;
- **HEPA type** (`hy-cf-hepa` >=99.97% H13): near-medical-grade particle interception, combined with activated carbon, for premium models / allergy-prone people / heavily polluted areas.

**[Editorial Opinion]** The `99.97%` of H13 refers to the interception rate **for 0.3 µm particles (the most penetrating particle size, MPPS)** — this is the definitional basis of the HEPA standard, and differs from the air filter's "ISO 5011 test-dust efficiency" basis; **the numbers must not be directly compared across categories**. Do not compare the cabin filter's 99.97% against the air filter's 99.5% to judge "which is more advanced" — they are not measuring the same kind of particle.

## III. Measurement methods

**[Framework Reference]**

1. **Particle efficiency**: reference the HEPA/EN 1822 or ISO 16890 framework, measuring the interception rate for a specific particle-size band (e.g. 0.3–2.5 µm);
2. **Gas adsorption**: adsorption efficiency and capacity tests of the activated carbon layer against specific gases (toluene/formaldehyde, etc.);
3. **Airflow / differential pressure**: measure differential pressure at nominal airflow to assess the impact on HVAC airflow.

## IV. Impact of parameters on user experience

**[Industry Knowledge]**

- **Excessive efficiency → reduced airflow**: HEPA media has high restriction; if the vehicle's HVAC blower is not matched, cooling/heating airflow will decrease. Therefore HEPA models must be matched to the vehicle's blower capability;
- **Activated carbon capacity**: activated carbon becomes "saturated"; after saturation adsorption fails but particle filtration continues. Therefore activated-carbon models should be replaced on a mileage schedule, with a shorter interval than pure particle models;
- **Dimension fit**: the cabin filter slot is a hard dimension; dimensional deviation causes air bypass leakage (unfiltered air entering directly through gaps).

---

*Continue reading: [Parameter Impact on Performance](parameter-performance.md)*
