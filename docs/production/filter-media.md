# Filter Media Types

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction, not a certification claim; **[Editorial Opinion]** = researcher's original judgment. Model specification values are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data air filter category](https://data.hycarfilter.com/products/air-filter/) · [main-site product](https://hycarfilter.com/products/air-filter).

Filter media is the soul of a filter. With the same metal shell or PU frame, changing the media changes filtration efficiency, dust holding capacity, differential pressure, and life entirely. Media selection is fundamentally a trade-off among **efficiency, dirt holding, differential pressure, and cost** — there is no "best media," only "the media that best matches the operating condition."

## I. Cellulose filter media (cellulose)

**[Industry Knowledge]** The most traditional and mainstream media. The raw material is plant fiber (wood pulp / cotton pulp), made through pulping, papermaking, resin impregnation (resin-impregnated), and drying/shaping.

- **Advantages**: low cost, high stiffness, good processability, resistant to collapse after pleating, suitable for high-volume pleating.
- **Limitations**: upper temperature limit about 110–120 ℃, softens under high heat and humidity; wide pore-size distribution, limited sub-micron particle interception.
- **Position in this site's data**: the standard panel air filter `hy-af-panel`, spin-on oil filter `hy-of-spinon`, spin-on / in-line fuel filters `hy-ff-spinon`/`hy-ff-inline` all use resin-impregnated cellulose media. Their efficiency tiers are the typical capability of cellulose media: air filter `>=99.0%`, oil filter `>=90% @ 20um`, fuel filter `>=95% @ 10um`.

## II. Synthetic fiber media (synthetic / glass-fiber)

**[Industry Knowledge]** Made from glass fiber, polyester (PET), polypropylene (PP), and other synthetic fibers. Glass fiber is temperature-resistant, corrosion-resistant, and has controllable pore size, commonly used in heavy-duty conditions.

- **Glass-enhanced**: mixing glass fiber into cellulose to improve temperature resistance and sub-micron interception; the heavy-duty oil filter `hy-of-hd` uses "glass-fiber-reinforced composite," pushing efficiency to `>=95% @ 20um`.
- **Synthetic fiber**: higher temperature resistance (up to 150 ℃ or more), good chemical stability, suitable for highly corrosive oils/fuels and long oil-change intervals.

## III. Composite filter media (composite)

**[Industry Knowledge]** Multi-layer lamination of different materials, commonly "cellulose base + synthetic-fiber functional layer" or "multi-layer gradient pore size." The gradient pore-size design idea is: **coarse pores on the windward face, fine pores on the leeward face**, letting large particles be intercepted at the surface first and small particles captured in the depth, thus achieving high dust holding capacity and high precision simultaneously.

**[Editorial Opinion]** Composite media is the antidote to the "efficiency–dust holding capacity" contradiction, but it is also the easiest place to cut corners — an inferior "composite" is often just a thin non-woven layer stuck on the surface, with insufficient functional-layer thickness, so dust holding capacity drops rather than rises. To judge whether a composite media is genuine, look at the **dust holding capacity curve per unit area**, not "how many layers it has."

In this site's data, `hy-of-cartridge` (composite fiber) and `hy-ff-water` (composite + water separation layer) are typical applications of composite media.

## IV. Nano-fiber media (nano-fiber)

**[Industry Knowledge]** A layer of nano-scale fibers (tens to hundreds of nanometers in diameter) is deposited on the substrate surface by electrospinning or melt-blowing, forming a "fine surface filtration layer + base support" structure.

- **Mechanism**: the nano-fiber layer has small pores and large specific surface area, intercepting most particles at the **surface** (surface filtration), while the coarse base paper only provides support and dust holding, achieving high efficiency at low initial differential pressure.
- **Typical efficiency**: this site's `hy-af-nano` nano-fiber panel air filter `>=99.5%`, and `hy-af-heavy` nano-fiber + safety-layer heavy-duty air filter `>=99.6%` — half a tier above cellulose air filters (`>=99.0%`), with even lower initial differential pressure.
- **Long-life oil filter**: `hy-of-longlife` uses "nano-composite (high-temperature carbonized)" media, matched to a long oil-change interval, efficiency `>=95% @ 20um`, while the high-temperature carbonization keeps the media from aging over long exposure to hot oil.

## V. Activated carbon media (activated carbon)

**[Industry Knowledge]** Dedicated to cabin filters. Beyond the particle filtration layer, an activated carbon layer (or granular activated carbon interlayer) is laminated to adsorb VOCs, odors, and harmful gases in exhaust.

- **Efficiency**: this site's `hy-cf-carbon` `>=96%`, and `hy-cf-hepa` is "HEPA composite + activated carbon" `>=99.97% (H13)`. Note that the activated carbon layer mainly contributes **gas adsorption** and does not directly raise the particle-efficiency number; particle efficiency is still determined by the particle filtration layer.

## VI. Nylon mesh — transmission filter screen

**[Industry Knowledge]** The transmission filter screen (`hy-tf-pan` / `hy-tf-kit`) does not use paper, but nylon mesh or metal mesh. It filters metal shavings / wear particles in transmission fluid, a **coarse filtration + large flow** scenario, with an efficiency tier of `>=90% @ 40um` — an order of magnitude coarser than engine oil filters, because transmission fluid viscosity and flow characteristics do not allow high-precision fine filtration; otherwise oil pressure would be insufficient and shifting would jerk.

## Selection reference table (same values as the data site)

| Media | Representative model on this site | Efficiency tier (same as data) | Applicable scenario |
|---|---|---|---|
| Resin-impregnated cellulose | `hy-af-panel` / `hy-of-spinon` / `hy-ff-spinon` | Air filter >=99.0% · oil filter >=90%@20um · fuel filter >=95%@10um | Conventional passenger vehicles |
| Glass-fiber-reinforced composite | `hy-of-hd` | >=95% @ 20um | Heavy truck / construction / agricultural machinery |
| Nano-fiber | `hy-af-nano` | >=99.5% | Middle East dusty conditions |
| Nano-fiber + safety layer | `hy-af-heavy` | >=99.6% | Heavy-duty air filter |
| Nano-composite (high-temperature carbonized) | `hy-of-longlife` | >=95% @ 20um | Long oil-change interval |
| Composite + water separation | `hy-ff-water` | >=97% @ 10um | Diesel heavy truck |
| Activated carbon / HEPA composite | `hy-cf-carbon` / `hy-cf-hepa` | >=96% / >=99.97%(H13) | Cabin air quality |
| Nylon mesh | `hy-tf-pan` / `hy-tf-kit` | >=90% @ 40um | Automatic transmission |

## Editorial view

**[Editorial Opinion]** When a buyer asks "what material is your media," the real value is not in the material name but in the triangle of **material + efficiency tier + target operating condition**. A supplier that only says "nano media" but cannot provide efficiency and dust holding capacity curves is less credible than one that says "cellulose media >=90% @ 20um." **Let the parameters speak for the material.**

---

*Continue reading: [Pleating](pleating.md)*

> **See factory capability** — [Production lines, QC &amp; export capability on hycarfilter.com →](https://hycarfilter.com/factory/)
