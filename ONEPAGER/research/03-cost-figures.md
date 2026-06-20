# 03 — Cost Figures: The NAHB Single-Source Estimate

This note documents the sourcing and arithmetic behind the "What the Tax Costs a Family"
block of [`/ONE-PAGER.md`](../../ONE-PAGER.md). It was revised in response to a PR review
comment directing that the calculation rest on a **single reputable, quotable source** that
provides both the total build cost and the materials portion, rather than a figure stitched
together from several cost-guide websites.

## I. The source

**National Association of Home Builders (NAHB), *Cost of Constructing a Home — 2024*** (Jan.
2025). The NAHB cost-of-construction survey is the homebuilding industry's standard annual
study and is the most reputable, widely quoted source for what it costs to build a new
single-family home in the United States. It is the single anchor for the figure on the page.

Per that survey:
- Average cost to **build** a new single-family home: **$428,215** (2024) — the highest in
  the survey's history (begun 1998).
- Average size: **2,647 sq ft**, or about **$162/sq ft** of finished floor area.
- Construction cost is **64.4%** of the average new-home sale price; the finished lot is the
  next-largest component at 13.7%.

## II. The materials share (the one derived input)

The NAHB survey reports total construction cost and breaks it into eight construction
**stages** (interior finishes ~24%, system rough-ins ~19%, framing ~17%, exterior finishes
~13%, and so on). It does **not** publish a single "materials vs. labor" percentage. The
materials share is therefore the **one derived input** in the calculation, and the page and
this note are transparent about that.

- **Figure used: ~40% of construction cost is materials.** This is the conservative end of
  the commonly cited 40–50% materials-to-construction-cost range, and it is consistent with
  NAHB's own commentary that recent cost growth has been driven as much by **labor** as by
  materials (i.e., materials are not the majority of the cost). Choosing the low end keeps
  the per-home figure defensible rather than inflated.

## III. The arithmetic (all from the single anchor)

| Step | Value |
|---|---|
| Average cost to build (NAHB 2024) | **$428,215** |
| Materials share (conservative, ~40%) | ~**$171,000** |
| Massachusetts sales/use tax rate | **6.25%** |
| **Tax on materials** | ~**$10,700** per home |

At a 50% materials share the tax would be ~$13,400; the page uses the ~40%/$10,700 figure as
the conservative statement.

## IV. The Greater Boston note (kept qualitative, to preserve the single source)

The NAHB figure is **national**. Massachusetts and Greater Boston build costs run well above
the national average (commonly reported around $300+/sq ft versus NAHB's ~$162/sq ft, i.e.,
roughly double), so the real Suffolk County number is **materially higher** than $10,700. To
keep the calculation anchored to one quotable source, the page states this **qualitatively**
("in Greater Boston ... the family's bill is materially higher") rather than multiplying in a
second source's per-square-foot figure. If a local figure is wanted, cite a single Greater
Boston construction-cost source for both inputs and redo the arithmetic from that one source.

## V. The compounding markup (paired point)

Separately from the build-cost figure, the page notes that the contractor's markup compounds
the tax: because a builder prices materials at cost plus margin and the tax is embedded in
that cost, the owner effectively pays **6.25% × (1 + margin)** — about **7.5%** at a 20%
markup, more at a wider one. This is an arithmetic identity, not a sourced statistic.

## VI. Before distribution

- Re-pull the NAHB figure for the **most recent** survey year available at the time of use.
- If the coalition prefers a **Greater Boston-specific** number, identify one reputable
  source that gives both the local total build cost and a materials share, and redo §III from
  that single source (replacing the national NAHB anchor).
- State the materials share as **derived** wherever the figure is quoted, so the one
  estimated input is never mistaken for a published NAHB statistic.

---

### Sources consulted

- NAHB, *Cost of Constructing a Home — 2024* (avg. build cost $428,215; ~$162/sq ft; 2,647 sq ft; construction = 64.4% of price; eight-stage breakdown) — [NAHB special study](https://www.nahb.org/news-and-economics/housing-economics-plus/special-studies/special-studies-pages/cost-of-constructing-a-home-in-2024); [NAHB blog](https://www.nahb.org/blog/2025/01/cost-of-construction-survey-2024); [Eye on Housing](https://eyeonhousing.org/2025/01/cost-of-constructing-a-home-in-2024/)
- Greater Boston / Massachusetts build cost running well above the national average (used only for the qualitative "materially higher" note) — [Houzeo (Boston)](https://www.houzeo.com/blog/how-much-does-it-cost-to-build-a-house-boston-ma/); [HomeGuide (MA)](https://homeguide.com/costs/cost-to-build-a-house-in-massachusetts)
