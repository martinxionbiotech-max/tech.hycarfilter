# In-Process Inspection (IPQC)

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Industry Knowledge]** = common industry practice; **[Framework Reference]** = standards framework introduction; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com).

In-Process Quality Control (IPQC) is the second gate — detecting and intercepting defects **during production** to prevent them from flowing into finished products. The core idea is "building quality into the process," rather than "picking out scrap after the fact."

## I. Pleat-height / pleat-pitch in-process inspection

**[Industry Knowledge]** In-process control points of the pleating step:

- **Pleat-height detection**: laser / vision in-process measurement of pleat height; on out-of-tolerance, alarm and stop the line or reject. Pleat-height deviation is the direct cause of air filters "not fitting the housing" or "air bypass leakage";
- **Pleat pitch / pleat count**: an encoder counts pleats, and vision detects pleat-pitch uniformity;
- **Crease-damage detection**: visual / vision identification of broken pleat tips and media cracks.

## II. In-process leak-tightness inspection

**[Industry Knowledge]** Spin-on oil filters / fuel filters undergo **inline 100% leak-tightness testing** after final assembly (see [Final Inspection](final-inspection.md) for details). The value of inline leak detection is that end cap bonding, housing sealing, and seal ring assembly leaks are **exposed on the spot**, without waiting until finished products are off the line to discover batch problems.

## III. Burst-pressure sampling

**[Industry Knowledge]** Static burst is a destructive test and cannot be done 100%, so **inline periodic sampling** is used (e.g. every 30 minutes / first article per shift): take a just-off-line filter, apply hydraulic pressure until rupture, record the burst pressure, and verify the stability of housing drawing, end cap curing, and seam crimping strength. First-article + periodic sampling is the standard action of an oil filter line.

## IV. Bypass valve opening-pressure calibration sampling

**[Industry Knowledge]** Bypass valve opening pressure is a key safety parameter, sampled in-process by frequency: a dedicated bench slowly increases pressure to verify that the opening-instant differential pressure falls within the calibrated range. On detecting drift, trace the bypass valve assembly of that batch.

## V. Process capability monitoring (SPC)

**[Industry Knowledge]** For key measurable parameters (pleat height, wall thickness, thread dimensions, seal ring hardness), perform **statistical process control (SPC)**: continuous sampling to plot control charts (X̄-R chart), triggering intervention once out of control limits. The value of SPC is **warning of trend drift before defects arise**, rather than reworking after scrap appears.

## Editorial view

**[Editorial Opinion]** The maturity of IPQC is judged by whether the boundary settings of "inline vs. offline" and "full inspection vs. sampling" are reasonable: what must be 100% (leak-tightness) must be inline full-inspected, what is destructive (burst) can only be periodic-sampled, and key safety parameters (bypass valve) need first-article + periodic. **Putting full inspection on the cutting edge and leaving sampling for destructive items is the basic skill of a process engineer.**

---

*Continue reading: [Final Inspection & Sampling (AQL)](final-inspection.md)*

> **See factory capability** — [Production lines, QC &amp; export capability on hycarfilter.com →](https://hycarfilter.com/factory/)
