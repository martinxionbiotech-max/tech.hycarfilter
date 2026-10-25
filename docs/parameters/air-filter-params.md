# Air Filter Key Parameters

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data air filter category](https://data.hycarfilter.com/products/air-filter/).

The air filter protects the engine's "respiratory system." Dust in the intake accelerates wear on cylinder liners, piston rings, and valves, so the core mission of the air filter is to **catch enough dust at low differential pressure**. This section breaks down the key parameters of the air filter and how they are measured.

## I. Parameter list

| Parameter | Definition | Same value on this site (data) |
|---|---|---|
| Filtration efficiency | Interception rate of test dust at nominal flow | `hy-af-nano` >=99.5% · `hy-af-heavy` >=99.6% · `hy-af-panel`/`hy-af-round` >=99.0% |
| Dust holding capacity | Cumulative dust weight accommodated before differential pressure reaches the terminal value (g) | Data is subject to the data site (not re-stored) |
| Initial differential pressure | Restriction of a brand-new element at nominal flow | Data is subject to the data site |
| Terminal differential pressure | Restriction at end of life (triggers replacement) | Framework value: approx. 6 kPa / 25 inH₂O |
| Filtration area | Unfolded filter media area | Determined by pleat height × pleat pitch × pleat count |
| Outer dimensions | Length × width × height / outer diameter × inner diameter × height | `hy-af-nano` 280×205×45 · `hy-af-round` Ø150/Ø80×320 · `hy-af-heavy` Ø200/Ø120×400 |

## II. Measurement methods

**[Framework Reference]** Per the ISO 5011 / SAE J726 framework:

1. **Efficiency**: On a test bench, continuously inject standard test dust (ISO 12103-1) at nominal flow and measure upstream/downstream dust concentration to obtain initial and weighted efficiency;
2. **Dust holding capacity**: Keep adding dust until differential pressure reaches the terminal value; the accumulated dust weight is the dust holding capacity;
3. **Differential pressure**: Use a differential pressure gauge (U-tube / electronic micro-differential) to measure static pressure difference across the element, recorded respectively at initial (clean) state and during dust loading.

## III. Impact of parameters on performance

**[Industry Knowledge]**

- **Efficiency ↑ → life ↑, but differential pressure ↑ and intake restriction ↑**: if the pores of an overly fine media are too small, it sacrifices intake volume, affecting engine power and fuel consumption;
- **Dust holding capacity ↑ → replacement interval ↑**: large dust holding capacity means resistance to fouling and less maintenance, especially valued in heavy-duty conditions;
- **Differential pressure ↑ → insufficient engine intake**: excessive differential pressure leads to a rich mixture, power loss, and higher fuel consumption.

**[Editorial Opinion]** The "optimal solution" for an air filter is to **maximize dust holding capacity and minimize differential pressure while meeting the target efficiency** — this is exactly the design value of nano-fiber filter media (`hy-af-nano`, `hy-af-heavy`): a fine surface filtration layer achieves high efficiency at low initial differential pressure, while the coarse base paper supports dust holding capacity. In dusty conditions (Middle East), prioritize **dust holding capacity + efficiency** rather than looking only at low price.

## IV. Dimension fit: the first gate of purchasing

**[Industry Knowledge]** The air filter is a "hard dimension" part — if it does not fit into the air cleaner housing, it fails completely. Dimensional deviation (length/width/height or outer/inner diameter/height) is the most frequent return reason for air filters. The dimensions on this site (e.g. `hy-af-nano` 280×205×45 mm) are identical to the data site; before ordering, confirm by reverse lookup against the OE number / vehicle model.

---

*Continue reading: [Oil Filter Key Parameters](oil-filter-params.md)*
