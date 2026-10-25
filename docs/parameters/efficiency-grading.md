# Filtration Efficiency Grading Framework

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Framework Reference]** = standards framework introduction (ISO 5011, SAE J726, etc.), **not constituting a certification claim**; **[Industry Knowledge]** = common industry practice; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com).

When a buyer sees "filtration efficiency 99.5%," the question they should ask first is: **under what test method, what particle size, and what flow rate was this 99.5% measured?** An efficiency number divorced from its test framework is meaningless. This section explains the standards frameworks behind efficiency grading.

## I. Three inseparable dimensions

**[Industry Knowledge]** Evaluating a filter by efficiency alone is one-sided; the industry recognizes three elements:

| Dimension | Meaning | Unit / expression |
|---|---|---|
| **Filtration efficiency** (efficiency) | Proportion of particles of a specific size intercepted | % (@ a given particle size um) |
| **Dust holding capacity** (dust holding capacity) | How much contaminant can be accommodated over service life | g (grams) |
| **Differential pressure** (pressure drop / restriction) | Resistance to fluid flow through the element | kPa / mbar / inH₂O |

There is a triangular trade-off among the three: **efficiency ↑ often means differential pressure ↑ and dust holding capacity ↓**. The ideal element minimizes differential pressure and maximizes dust holding capacity while meeting the target efficiency.

## II. Air filters: the ISO 5011 framework

**[Framework Reference]** ISO 5011 is the test-standard framework for **air filters of internal-combustion-engine intake systems**, specifying bench test methods, centered on:

- **Filtration efficiency**: inject standard test dust (e.g. ISO 12103-1 A2 fine / A4 coarse) at nominal flow, measure upstream/downstream concentration difference to obtain **initial efficiency** and **weighted efficiency**;
- **Dust holding capacity**: keep adding dust until differential pressure reaches the terminal value (e.g. 6 kPa or 25 inH₂O); the accumulated dust weight is the dust holding capacity;
- **Initial/terminal differential pressure**: the initial restriction at nominal flow and the restriction at the end of dust loading.

**[Industry Knowledge]** In practice, the "efficiency % at rated flow" is commonly quoted; this site's air filter efficiency tiers (`hy-af-nano` `>=99.5%`, `hy-af-heavy` `>=99.6%`, `hy-af-panel`/`hy-af-round` `>=99.0%`) are the nominal values under this framework, subject to the data site.

## III. Air filters: the SAE J726 framework

**[Framework Reference]** SAE J726 is the **air filter test procedure** framework commonly used in North America, sharing the same origin as ISO 5011 and likewise measuring efficiency, dust holding capacity, and differential pressure. The two differ slightly in dust particle-size grading and terminal differential pressure settings, but the **core logic is identical**: add dust → measure efficiency → accumulate dust holding → observe differential pressure rise.

**[Editorial Opinion]** When encountering a "conforms to SAE J726" claim during purchasing, be aware that it is a **test-method framework**, not a "quality certification" — it tells you where the number came from, not whether the number meets a requirement. Real credibility comes from **third-party laboratory reports + explicitly stated test conditions**.

## IV. Oil filters: the ISO 4548 framework

**[Framework Reference]** ISO 4548 is the test-method framework for **oil filters**, with key items:

- **Filtration efficiency / particle counting**: ISO 4548-12 uses the multi-pass method, injecting standard test dust and measuring filtration efficiency at various particle sizes (e.g. 20 µm);
- **Bypass valve characteristics**: measure bypass valve opening pressure and differential-pressure–flow characteristics;
- **Static burst pressure**: measure the pressure-resistance limit of the housing and element;
- **Fatigue / pulsation**: durability simulating oil-pressure pulsation.

**[Industry Knowledge]** This site's oil filter efficiency tiers `hy-of-spinon`/`hy-of-cartridge` `>=90% @ 20um`, `hy-of-hd`/`hy-of-longlife` `>=95% @ 20um` — **"@ 20um" explicitly states the particle size**, which is far more rigorous than a bare "99%" (efficiency for 20 µm particles).

## V. Fuel filters: the ISO 4020 / ISO 19438 framework

**[Framework Reference]**

- **ISO 4020**: test-method framework for diesel fuel filters;
- **ISO 19438**: the **filtration efficiency and particle counting** multi-pass framework for fuel filters, defining nominal/absolute micron ratings;
- Also note the **water separation efficiency** test (diesel water separation).

**[Industry Knowledge]** Fuel filters use finer micron ratings: this site's `hy-ff-spinon`/`hy-ff-inline` `>=95% @ 10um`, water-separating type `hy-ff-water` `>=97% @ 10um` — fuel injection systems are sensitive to 5–10 µm particles, so fuel filter precision is generally finer than oil filters.

## VI. Three bases of efficiency rating (avoiding pitfalls)

**[Industry Knowledge]** The same element can yield wildly different efficiency numbers under different rating bases:

1. **Nominal rating**: efficiency of roughly 50% at a given particle size — an inflated number;
2. **Absolute rating**: efficiency of 98.7% or 99% at a given particle size — a more solid number;
3. **Beta ratio (βx)**: βx = upstream particle count / downstream particle count (for x µm); β₁₀(c) ≥ 200 commonly corresponds to the filtration-precision expression of ISO 19438 — the most rigorous.

**[Editorial Opinion]** When comparing prices, always align the efficiency basis before comparing — "99%@20um (absolute)" and "99% (nominal)" are not the same thing at all. **Only numbers that state particle size, absolute rating, and test method can be compared horizontally.**

---

*Continue reading: [Air Filter Key Parameters](air-filter-params.md)*
