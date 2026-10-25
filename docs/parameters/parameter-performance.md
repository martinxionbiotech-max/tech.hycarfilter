# Parameter Impact on Performance

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com).

The preceding pages each covered individual parameters; this page does a **horizontal synthesis** — linking "efficiency, differential pressure, dust holding capacity, precision, life" together to explain how they trade off against each other, and how buyers should make trade-offs according to operating conditions.

## I. The core triangular trade-off

**[Industry Knowledge]** The "impossible triangle" of filtration systems: **efficiency, differential pressure, and dust holding capacity** cannot all be optimal at once.

```
Efficiency ↑  →  fine pores, dense fibers  →  differential pressure ↑ , dust holding capacity ↓
Dust holding capacity ↑  →  thick media, deep dirt holding  →  large volume, cost ↑
Differential pressure ↓  →  large area or coarse pores  →  area limited by outer shape / efficiency ↓
```

**Ways to break the deadlock**:

1. **Increase filtration area** (pleat height ↑ pleat count ↑) — without changing the media, larger area lowers differential pressure and raises dust holding capacity, but is limited by the outer-shape volume;
2. **Gradient / composite media** — fine surface filtration + coarse deep dirt holding, achieving efficiency and dust holding capacity simultaneously;
3. **Nano-fiber surface filtration** — high efficiency at low initial differential pressure, with the base layer supporting dust holding capacity.

## II. The "tier logic" of efficiency and precision

**[Editorial Opinion]** This site's per-category efficiency tiers (same as the data site) are not arbitrary but are **determined by the protected object**:

| Category | Precision tier | Why this tier |
|---|---|---|
| Cabin filter | 95% → 99.97%(H13) | Protects people; can use HEPA, but limited by airflow |
| Air filter | 99.0% → 99.6% | Protects cylinder liners; high dust holding first, fine dust interception |
| Oil filter | 90–95% @ 20um | Main oil gallery; restriction must not be high; 20 µm tier balances |
| Fuel filter | 95–97% @ 10um | Protects injectors; precision must be fine (10 µm) |
| Transmission filter screen | 90% @ 40um | Coarse filtration, large flow; 40 µm tier preserves oil pressure |

**[Editorial Opinion]** Seeing these numbers, a buyer should form an intuition: **precision from fine to coarse = fuel filter (10µm) > oil filter (20µm) > transmission filter screen (40µm)**. This is not about quality, but about **each protected object's differing sensitivity to particulates**. Injectors fear fine particles more than crankshaft bearings do, and transmission oil pressure does not allow fine filtration. **"The finer the precision the better" is layman talk; matching the operating condition is professional judgment.**

## III. Differential pressure: the underestimated performance killer

**[Industry Knowledge]** Differential pressure (restriction) directly translates into fuel consumption/power loss and life:

- Air filter differential pressure too high → insufficient intake → rich mixture → fuel consumption ↑, power ↓;
- Oil filter differential pressure too high → bypass valve opens frequently → filtration is bypassed;
- Cabin filter differential pressure too high → airflow ↓ → cooling/heating degrades.

**[Editorial Opinion]** When inspecting goods, buyers often look only at the "efficiency rating" and rarely ask about "initial differential pressure" and "terminal differential pressure." **An element with a pretty efficiency but absurdly high differential pressure merely swaps one problem for another.** A rigorous supplier provides three curves — efficiency–differential pressure–dust holding capacity; a supplier with only a single efficiency number deserves a question mark.

## IV. Life = dust holding capacity × usage intensity

**[Industry Knowledge]** Filter life is not a fixed mileage but **dust holding capacity ÷ dust generation per unit mileage**. The same air filter, in a dusty condition (Middle East / mines), may have a mileage life of only 1/3–1/5 of that in a clean condition. Therefore:

- **Dust holding capacity** is a hard indicator of "anti-fouling" capability; heavy-duty / severe conditions prioritize dust holding capacity;
- **Long oil-change-interval oil filters** (`hy-of-longlife`) use nano-composite media precisely to maintain efficiency and dirt holding over a longer oil mileage.

## V. Purchasing decision quick reference

**[Editorial Opinion]**

| Operating condition | Priority parameters | Recommended direction |
|---|---|---|
| Dusty (Middle East / mines) | Dust holding capacity + efficiency | Nano / heavy-duty air filter `hy-af-nano`/`hy-af-heavy` |
| Long oil-change interval (Europe/US) | Sustained efficiency + high-temperature resistance | Long-life oil filter `hy-of-longlife` |
| Low-quality diesel (Africa/Southeast Asia) | Water separation + precision | Water-separating fuel filter `hy-ff-water` |
| Urban commuting | Odor adsorption | Activated-carbon cabin filter `hy-cf-carbon` |
| Air pollution / allergy | Particle interception | HEPA cabin filter `hy-cf-hepa` |

---

*This is the end of the Technical Parameters section; next section: [Testing & Quality Control](../qc/incoming-inspection.md)*
