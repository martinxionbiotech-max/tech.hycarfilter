# Hycarfilter Tech — Filter Industry Standards Layer

> **Positioning**: This subsite is an **industry standards layer** designed to be "searched and cited" — production technology / technical parameters / testing & quality control / industry standards.
> It has zero overlap with the main site's marketing, and does not duplicate the data site's product values: **the data site answers "what are the parameters of this model," while the tech site answers "how is this parameter made, how is it measured, and on what basis does it hold."**

## Why this layer is needed

What a buyer ultimately purchases is not a slogan like "high-efficiency filter," but whether three things can be verified:

1. **How it is made** — how filter media is selected, how it is pleated, how end caps are bonded, how the whole line runs;
2. **How parameters are defined** — under what standards framework values like filtration efficiency, dust holding capacity, and differential pressure hold;
3. **How stability is guaranteed** — how incoming materials are inspected, how the process is controlled in-line, how finished products are fully/sampled inspected, and how outgoing shipments are verified.

Marketing copy cannot explain these three things, and a product database cannot store them; only a technical layer can carry them. Every page of the tech site answers "on what basis."

## Four-layer interlink structure

```
hycarfilter.com        (Astro commercial main site)   → convinces the buyer "why buy"
data.hycarfilter.com   (MkDocs product database)      → single source of truth for models/specs "what the parameters are"
tech.hycarfilter.com   (MkDocs technical standards)   → this repo "how it's made / how it's measured / on what basis"
market.hycarfilter.com (MkDocs industry reports)      → "how this product sells in which market"
```

Interlink rule: main-site product page → data model detail → **tech process/testing page** → market regional report. Each page of this repo links back at the top to the corresponding data-site category and main-site product, ensuring the path "from spec to process" for the buyer is never broken.

## Section overview

| Section | Pages | Question answered |
|---|---|---|
| [Production Process](production/filter-media.md) | 6 | How filter media is selected/pleated, how end caps are bonded, how spin-on oil filters are assembled, how category lines differ, what equipment is used |
| [Technical Parameters](parameters/efficiency-grading.md) | 6 | Under what framework efficiency grading holds, how each category's key parameters are defined and measured, how parameters affect performance |
| [Testing & Quality Control](qc/incoming-inspection.md) | 6 | How incoming materials are inspected, how the process is controlled in-line, how finished products are fully/sampled inspected, what equipment is used, how defects are prevented, how outgoing shipments are verified |
| [Industry Standards](standards/iso-sae.md) | 2 | What the ISO/SAE/GB standards frameworks are, where the main export markets' standards differ |
| [Technical Q&A](qa/index.md) | 1 | The most frequently asked technical questions from buyers, answered from an original perspective |

## Source-attribution conventions

All content in this repo follows one attribution discipline: a note at the top of each page declares it, and the body distinguishes it with inline tags:

- **[Industry Knowledge]** — common filter-industry practices and public consensus, not bound to any single manufacturer;
- **[Framework Reference]** — introduction to international/national standards frameworks (ISO 5011, SAE J726, etc.), **provided only as industry-common-knowledge framework, not constituting a certification claim**;
- **[Editorial Opinion]** — the researcher's original subjective judgment, attributed to Xiaozhu ✍️, for reference in purchasing decisions.

## Data-consistency statement

All **dimension / efficiency / material / thread / seal** values cited in this repo are identical to those in the canonical dataset `data/products.json` on [data.hycarfilter](https://data.hycarfilter.com); any model specification takes the data site as its single source of truth. This repo only carries "process and standards knowledge" and does not re-store product values.

---

*Next: start with [Filter Media Types](production/filter-media.md) to enter Production Process.*
