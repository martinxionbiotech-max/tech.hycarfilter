# Final Inspection & Sampling (AQL)

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = AQL sampling framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com). Backlinks: [data home](https://data.hycarfilter.com).

Finished-product inspection is the third gate, with one core question: **which items must be 100% full-inspected, and which can be sampled by AQL?** Getting the split wrong means either missing fatal defects or inflating cost.

## I. Items that must be 100% full-inspected (safety-critical)

**[Industry Knowledge]** Once the following items fail, it is a **leak / oil-starvation / filtration-failure**-grade accident, so every unit must be inspected:

| Item | Category | Method |
|---|---|---|
| **Leak-tightness** | Spin-on oil filter, fuel filter | Inline pressurize-and-hold / differential-pressure leak detection; reject on excessive pressure drop |
| **Thread go/no-go** | Spin-on oil filter / fuel filter | Go/no-go gauge 100% pass inspection |
| **Seal ring assembly** | Spin-on filter | Visual / sensor confirmation of proper seating, no flipping |
| **Outer dimensions** | Air / cabin filter (hard-dimension parts) | Gauge 100% pass inspection (scrap if it won't fit the housing) |

**[Industry Knowledge]** The "100% leak-tightness test" of spin-on oil filters is an iron rule of the industry — because leakage cannot be seen visually and the consequence is fatal, it cannot be covered by sampling. This is also a point repeatedly emphasized in the source site's "quality oil filter vs. inferior oil filter" comparison (100% leak-tightness).

## II. Items sampled by AQL (non-destructive, acceptable trace defects)

**[Framework Reference]** The AQL (Acceptable Quality Limit) framework (ISO 2859 / GB/T 2828) determines sample size n and accept/reject numbers Ac/Re according to **lot size → inspection level → AQL value**. Typical applications:

| Item | AQL tier (reference) | Description |
|---|---|---|
| Appearance defects (scratches / stains / printing) | AQL 1.0–2.5 | Minor defects |
| Dimensions (non-critical) | AQL 1.0 | Functional dimensions |
| Packaging / labels | AQL 1.5–4.0 | Packing, label correctness |

**[Editorial Opinion]** AQL is not an excuse to "allow a certain proportion of defective goods into the customer's hands," but the **statistical language of sampling acceptance**: AQL 1.0 means that under that sampling plan, the whole lot's "acceptable quality limit" is 1%. When buyer and supplier agree on acceptance, they must **simultaneously agree on the AQL value, inspection level, and defect grading (critical / major / minor)**; otherwise "sampling" is an empty word.

## III. Sampling of destructive tests on finished products

**[Industry Knowledge]** Destructive items cannot be full-inspected; they are sampled **by frequency / batch**:

- Static burst: first article + periodic sampling;
- Filtration efficiency / dust holding capacity: sampled by batch and sent to the laboratory (long cycle, see [Laboratory Equipment](lab-equipment.md));
- Bypass valve opening pressure: batch sampling.

## IV. The combination logic of full inspection + sampling

**[Industry Knowledge]** The mature scheme is a three-layer stack of "**safety-critical items 100% full-inspected + appearance/minor items AQL-sampled + destructive items batch-sampled**." All three are indispensable: full inspection without sampling → cost out of control and appearance defects slip through; sampling without full inspection → fatal leaks are missed.

## Editorial view

**[Editorial Opinion]** During a factory audit, asking "of your finished-product inspection, which items are full-inspected, which are sampled, what is the AQL, and how are defects graded" is a hundred times more useful than asking "do you have quality control." **A factory that can state the full-inspection/sampling boundary and the AQL value is one that truly runs quality control as a system.**

---

*Continue reading: [Laboratory Equipment](lab-equipment.md)*

> **See factory capability** — [Production lines, QC &amp; export capability on hycarfilter.com →](https://hycarfilter.com/factory/)
