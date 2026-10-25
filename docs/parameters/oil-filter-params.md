# Oil Filter Key Parameters

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data oil filter category](https://data.hycarfilter.com/products/oil-filter/).

The oil filter works under high temperature, high pressure, and pulsating oil flow, and must also hold oil pressure during cold-start moments. Its parameters are more "danger-sensitive" than other categories — a single parameter failure can cause oil starvation or leakage. This section breaks down the key parameters of the oil filter.

## I. Parameter list

| Parameter | Definition | Same value on this site (data) |
|---|---|---|
| Filtration efficiency | Interception rate of 20 µm particles (absolute rating) | `hy-of-spinon`/`hy-of-cartridge` >=90% @ 20um · `hy-of-hd`/`hy-of-longlife` >=95% @ 20um |
| Thread specification | Thread mating with the oil-pan fitting | `hy-of-spinon` 3/4-16 UNF · `hy-of-hd` 1-12 UNF · `hy-of-longlife` 3/4-16 UNF |
| Bypass valve opening pressure | Differential pressure at which the bypass valve opens | Data is subject to the data site (calibrated parameter) |
| Anti-drainback valve | Prevents oil backflow when the engine is stopped | All spin-on oil filters are equipped |
| Burst pressure | Pressure-resistance limit of housing / element | Framework test item |
| Seal ring | Mating-surface seal | NBR (high/low temp resilient) |
| Outer dimensions | Height × outer diameter | `hy-of-spinon` Ø76×90 · `hy-of-hd` Ø118×210 |

## II. Measurement methods

**[Framework Reference]** Per the ISO 4548 framework:

1. **Efficiency**: ISO 4548-12 multi-pass method, injecting standard dust and particle-counting to obtain efficiency at each particle size (this site uses the 20 µm tier);
2. **Bypass valve**: a dedicated bench slowly increases pressure and records the differential pressure at the instant the bypass valve opens, verifying the calibrated opening pressure;
3. **Static burst**: plug the oil outlet and apply hydraulic pressure until the housing/element ruptures, recording the burst pressure;
4. **Anti-drainback valve**: invert and measure leakage to verify rebound sealing.

## III. Impact of parameters on performance

**[Industry Knowledge]**

- **Efficiency vs oil differential pressure**: the oil filter sits on the main oil gallery; excessive restriction raises bypass valve opening frequency and affects oil-pressure buildup. Therefore oil filter precision is not as fine as fuel filters (20 µm tier rather than 10 µm tier) — this is a **trade-off determined by operating conditions**;
- **Bypass valve opening pressure**: calibrated too high → risk of oil starvation with high-viscosity oil during cold start; calibrated too low → normal filtration is bypassed. It must match the vehicle's oil-pump characteristics;
- **Anti-drainback valve**: poor rebound → oil backflow when stopped → slow oil-pressure buildup on next start, aggravating cold-start wear;
- **Burst pressure**: reflects the strength margin of the housing (one-piece drawn) and end cap bonding — a safety bottom line.

## IV. Editorial view: the oil filter is a "valve assembly," not just a "filter element"

**[Editorial Opinion]** Many buyers focus only on the oil filter's "filtration efficiency," overlooking that the oil filter conceals **two valve assemblies: the bypass valve + the anti-drainback valve**. These two valves are what essentially distinguish the oil filter from air/cabin filters — they determine **the safety of the oil circuit at extreme moments**. Even if an oil filter has mediocre media, reliable valves can save it; no matter how good the media, a stuck bypass valve can still cause oil starvation. **When evaluating an oil filter, look at the valves first, then the media.**

---

*Continue reading: [Fuel Filter Key Parameters](fuel-filter-params.md)*
