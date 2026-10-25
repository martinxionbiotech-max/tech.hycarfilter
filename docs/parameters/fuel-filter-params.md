# Fuel Filter Key Parameters

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data fuel filter category](https://data.hycarfilter.com/products/fuel-filter/) · [main-site fuel filter category](https://hycarfilter.com/products/fuel-filter/).

Fuel injection systems (especially high-pressure common-rail diesel) are extremely sensitive to particulates — the injector nozzle clearance is only a few microns, and a single hard particle can seize an injector. Fuel filter precision is therefore generally finer than oil filters, and diesel filters must also provide **water separation**.

## I. Parameter list

| Parameter | Definition | Same value on this site (data) |
|---|---|---|
| Filtration efficiency | Interception rate of 10 µm particles | `hy-ff-spinon`/`hy-ff-inline` >=95% @ 10um · `hy-ff-water` >=97% @ 10um |
| Micron rating | Nominal/absolute rated particle size | 10 µm (absolute-rating basis) |
| Water separation efficiency | Ability of a diesel filter to separate free water | `hy-ff-water` composite + water separation layer |
| Flow rate | Fuel delivery capability at nominal flow | Data is subject to the data site |
| Thread / connection | Spin-on thread / quick-connect fitting | `hy-ff-spinon`/`hy-ff-water` M16x1.5 · `hy-ff-inline` quick-connect O-ring |
| Outer dimensions | Height × outer diameter (spin-on) / length × outer diameter (in-line) | `hy-ff-spinon` Ø85×140 · `hy-ff-inline` Ø30×90 · `hy-ff-water` Ø90×165 |

## II. Measurement methods

**[Framework Reference]** Per the ISO 4020 / ISO 19438 framework:

1. **Efficiency / particle counting**: ISO 19438 multi-pass method, using Beta ratio or absolute rating to characterize precision (this site uses the 10 µm tier);
2. **Water separation**: mix a measured amount of free water into the diesel and measure residual water after filtration to obtain water separation efficiency;
3. **Flow–differential pressure**: measure differential pressure at nominal flow to verify fuel delivery capability.

## III. Impact of parameters on performance

**[Industry Knowledge]**

- **Precision (10 µm) vs differential pressure**: fuel has low viscosity and is flow-sensitive; overly fine precision raises differential pressure and affects injection pressure supply. The 10 µm tier is the common balance point for passenger/light-commercial diesel filters;
- **Water separation**: water in diesel causes injector corrosion, microbial growth, and winter icing that blocks the filter. A diesel filter without water separation will fail quickly in humid/low-quality-diesel regions (Southeast Asia, Africa);
- **Fuel compatibility**: seals / rubber compounds / housings must withstand gasoline, diesel, and biodiesel, otherwise they swell and leak.

## IV. Editorial view: diesel filters focus on "water separation," gasoline filters on "quick-connect sealing"

**[Editorial Opinion]** The purchasing focus for fuel filters varies by fuel: for **diesel filters**, the core differentiator is water separation efficiency — low-quality-diesel regions (Africa, Southeast Asia, parts of the Middle East) must use the water-separating type (`hy-ff-water`), otherwise aftermarket failures are inevitable; for **gasoline filters** (in-line type `hy-ff-inline`), the core is the O-ring seal and pressure resistance of the quick-connect fitting — a leak is a safety hazard. **Do not buy "fuel filter" as a single category; first ask whether it is for diesel or gasoline and whether water separation is needed.**

---

*Continue reading: [Cabin Filter Key Parameters](cabin-filter-params.md)*
