# ISO / SAE Standards Framework

!!! note "Source attribution"
    This article is an editorially original synthesis. **[Framework Reference]** = international/national standards framework introduction, **provided only as industry common knowledge, not constituting any certification claim**; **[Industry Knowledge]** = common industry practice; **[Editorial Opinion]** = researcher's original judgment. Model specifications are subject to [data.hycarfilter](https://data.hycarfilter.com).

This section introduces the international/national standards frameworks related to filters. **Important statement: the following are all common-knowledge introductions to "test-method / requirement frameworks"; hycarfilter does not claim to hold any certification based on them.** Buyers should understand standards as "a coordinate system for understanding where parameters come from," not "a product certificate of conformity."

## I. Standards framework overview

| Standard | Applicable object | Core content (framework) |
|---|---|---|
| **ISO 5011** | Internal-combustion-engine intake air filters | Bench test: filtration efficiency, dust holding capacity, differential pressure |
| **SAE J726** | Air filters | North American test-procedure framework, efficiency / dust holding capacity / differential pressure |
| **ISO 4548** | Oil filters | Efficiency (multi-pass), bypass valve, static burst, fatigue |
| **ISO 4020** | Diesel-engine fuel filters | Test-method framework |
| **ISO 19438** | Fuel filters | Filtration efficiency and particle counting (Beta ratio / absolute rating) |
| **ISO 16890** | Air purification / cabin filters | Particle classification (ePM classification framework) |
| **GB/T 13549 series** | Automotive filters (China) | Chinese automotive filter test-method series |

## II. Detailed explanation of each standards framework

### ISO 5011 (air filters)

**[Framework Reference]** Defines the test method for internal-combustion-engine intake air filters: using standard test dust (ISO 12103-1) at nominal flow to measure **initial / weighted filtration efficiency**, **dust holding capacity** (to the terminal differential pressure), and **initial / terminal differential pressure**. It is the framework underlying this site's air filter efficiency tiers (`hy-af-*` `>=99.0%`–`>=99.6%`).

### SAE J726 (air filters, North America)

**[Framework Reference]** Shares the same origin as ISO 5011 and is commonly used in North America. The core logic is identical (add dust → efficiency → dust holding → differential pressure), with differences in details such as dust classification and terminal differential pressure settings. **The two frameworks must not be mixed** — the same element may yield different numbers under the two frameworks, and the nominal value must state which framework is used.

### ISO 4548 (oil filters)

**[Framework Reference]** Oil filter test methods, in multiple parts:

- **4548-12**: filtration efficiency (multi-pass method, particle counting);
- bypass valve characteristics, static burst pressure, fatigue / pulsation, etc.

This site's oil filter efficiency `>=90% @ 20um`/`>=95% @ 20um` is the particle-efficiency basis under this framework.

### ISO 4020 / ISO 19438 (fuel filters)

**[Framework Reference]** ISO 4020 is the test-method framework for diesel fuel filters; ISO 19438 focuses on **filtration efficiency and particle counting**, using Beta ratio to define filtration precision (e.g. β₁₀(c) ≥ 200), and also covers water separation. This site's fuel filter `>=95% @ 10um`/`>=97% @ 10um` is the absolute-rating basis.

### GB/T 13549 series (China)

**[Framework Reference]** The Chinese automotive filter test-method series standards framework, corresponding to the ISO series, is a common test basis for domestic factories.

## III. The boundary between standards and "certification"

**[Editorial Opinion]** This is the point this section most wants to emphasize: **standard ≠ certification**.

- **Standard**: specifies "how to measure, how indicators are defined" — it is a method anyone can follow;
- **Certification**: a third-party organization "proves you conform to a standard / system" — it is an endorsement that requires a certificate.

"A product conforms to the ISO 5011 test framework" and "a product passed ISO 5011 certification" are two different things — the former is a method statement, while the latter does not hold (ISO 5011 is itself a test-method standard, not a certifiable system certification). **Buyers should be wary of the phrase "ISO 5011 certification," which is usually marketing-copy misuse; the correct expression is "tested per the ISO 5011 framework."**

Likewise, **ISO 9001 (quality system) and IATF 16949 (automotive quality system)** are system certifications (certifiable); the two entries appearing in this site's data set represent "quality management system frameworks," not a performance endorsement for each model.

## IV. How buyers should use standards

**[Editorial Opinion]**

1. **Look at the test method**: ask which standard the efficiency number is based on, what particle size, and absolute or nominal rating;
2. **Ask for third-party reports**: curves / reports measured per the standards framework are more credible than verbal claims;
3. **Beware of wording**: any "XX standard certification" or "conforms to XX standard" without stated test conditions warrants follow-up questioning of the details.

---

*Continue reading: [Major Export Market Standards Differences](export-market-diff.md)*
