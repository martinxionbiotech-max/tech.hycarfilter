# Hycarfilter Phase 5 — tech.hycarfilter Technical Standards Layer Delivery Report

> Output date: 2026-10-25 ｜ Author: content architect from a filter process engineer's perspective + industry researcher (Xiaozhu ✍️)
> Repo: `tech.hycarfilter` (MkDocs · production technology/parameters/testing/quality control/industry standards) ｜ Basis: `docs/hycarfilter-p1-inventory-architecture.md` §2.3 + data-site deliverable `data.hycarfilter/data/products.json`

---

## 1. Delivery overview

The MkDocs Material technical subsite is live, positioned as the "industry standards layer to be searched and cited" — **zero overlap with main-site marketing, no duplication of data-site product values** (data = product values, tech = process and standards knowledge). Chinese industry knowledge + international standards frameworks integrated, all original writing site-wide.

## 2. Site scale

| Section | Pages | Content |
|---|---|---|
| Home | 1 | Positioning / four-layer interlink / source-attribution conventions / data-consistency statement |
| Production Process | 6 | Filter media types · Pleating process · End cap bonding & curing · Spin-on oil filter assembly line · Category production-line differentiation · Production-line equipment |
| Technical Parameters | 6 | Efficiency grading framework · Air filter parameters · Oil filter parameters · Fuel filter parameters · Cabin filter parameters · Parameter impact on performance |
| Testing & Quality Control | 6 | Incoming inspection (IQC) · In-process inspection (IPQC) · Final inspection & sampling (AQL) · Laboratory equipment · Defects & prevention · Export/outgoing inspection (OQC) |
| Industry Standards | 2 | ISO/SAE standards framework · Export market standards differences |
| Technical Q&A | 1 | 15 buyer technical questions answered originally |
| **Total** | **22** | (+ 404 = 23 HTML) |

**Q&A count**: 15 items (within the 10–15 upper-limit requirement line).

## 3. Discipline execution

1. **Data consistency**: All site-wide cited dimension/efficiency/material/thread/seal values are identical to `data.hycarfilter/data/products.json` — efficiency tiers (air filter 99.0%–99.6%, oil filter 90–95%@20um, fuel filter 95–97%@10um, cabin filter 95%–99.97%H13, transmission filter screen 90%@40um), threads (3/4-16 UNF / 1-12 UNF / M16x1.5), outer dimensions (280×205×45, Ø150/Ø80×320, Ø200/Ø120×400, Ø76×90, Ø118×210, Ø85×140, Ø30×90, Ø90×165, 240×200×30), HS codes (8421310000/8421230000/8512400000/8708409990/8512209000) verified item by item, **0 conflicts**. Model naming follows the data site's `hy-{category code}-{series}` (not the Phase 1 draft `HF-` prefix).
2. **Certification wording**: ISO 5011/SAE J726 and similar are always labeled "standards framework / common requirements / reference," with a separate "standard ≠ certification" boundary note; IATF 16949/ISO 9001 are only expressed as "quality management system framework," **not claiming to hold certification**.
3. **Source-attribution marking**: A note declaration at the top of each page + inline tags `[Industry Knowledge]` / `[Framework Reference]` / `[Editorial Opinion]` three-state marking, with editorial opinions attributed to "Xiaozhu ✍️".

## 4. build / commit / push

- **build**: `mkdocs build` ✅ 22 content pages + 404, 0.64s, Material theme (language=zh, teal palette), 0 WARNING / 0 ERROR.
- **commit**: `b7c8d7e` `p5-tech: scaffold tech/standards/QC layer (MkDocs Material)`.
- **push**: origin/main (new branch `main` pushed).
- **sync**: 0 conflicts with data-site values (verified item by item).

## 5. Compact Chinese report

**Site scale**: 22 content pages = Home 1 · Production Process 6 · Technical Parameters 6 · Testing & Quality Control 6 · Industry Standards 2 · Technical Q&A 1 (15 items).

**Section scale**: Process 6 pages (filter media types/pleating/end cap bonding/spin-on assembly/category differentiation/equipment) · Parameters 6 pages (efficiency grading framework + air/oil/fuel/cabin filter parameters + parameter impact) · Testing 6 pages (IQC/IPQC/finished-product AQL/laboratory/defect prevention/outgoing OQC) · Standards 2 pages (ISO/SAE framework + export market differences) · Q&A 15 items.

**Consistency check**: efficiency/dimension/thread/HS codes item-by-item identical to `data.hycarfilter/products.json`, 0 conflicts; naming follows `hy-{category code}-{series}`; certification items always use "standards framework" wording; each page marked with three-state source attribution.

**build**: mkdocs build 22 pages all green, 0 warnings. **commit**: `p5-tech: scaffold tech/standards/QC layer`. **push**: origin/main. **sync**: 0/0.

**Report path**: `docs/p5-tech-site-report.md` (this document).
