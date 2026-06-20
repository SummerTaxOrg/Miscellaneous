# 03 — Cost Figures: The Suffolk County Estimate

This note documents the sourcing and arithmetic behind the "What the Tax Costs a Family in
Suffolk County" block of [`/ONE-PAGER.md`](../../ONE-PAGER.md), added in response to a PR
review comment asking for researched material costs for a recent single-family home in
Suffolk County, Massachusetts.

## I. The honest caveat first

There is **no single authoritative figure** for "the materials cost of a new single-family
home in Suffolk County." County-level new-construction cost data is not published at that
granularity. The figure on the one-pager is therefore a **transparent estimate built from
three reputable, current inputs**: (1) Greater Boston cost-to-build per square foot, (2) the
average size of a new single-family home, and (3) the materials share of construction cost
from the national homebuilders' association survey. Each input and the arithmetic are shown
below so the number can be defended, challenged, or refined.

## II. The inputs

| Input | Value used | Source |
|---|---|---|
| Cost to build, Greater Boston | **$300–$350 / sq ft** (builder-grade; custom runs higher) | 2025 Massachusetts/Boston builder cost surveys (Houzeo, HomeGuide, Angi) |
| Average new single-family home size | **~2,400 sq ft** (U.S. average 2024; median 2,210) | U.S. Census / NAHB, via Eye on Housing (2025) |
| Total construction cost (derived) | **~$720,000–$840,000**, rounded to **~$780,000** | 2,400 sq ft × $300–$350 |
| Materials share of construction cost | **~40–50%** | NAHB *Cost of Constructing a Home, 2024* and related analyses |
| **Taxable materials (derived)** | **~$310,000–$390,000** | $780,000 × 40–50% |
| MA sales/use tax rate | **6.25%** | G.L. c. 64H/64I |
| **Tax on materials (derived)** | **~$19,000–$24,000** | $310,000–$390,000 × 6.25% |

## III. National anchor for sanity-checking

The NAHB *Cost of Constructing a Home, 2024* survey puts the average **national** construction
cost (excluding land) at about **$428,000**, roughly **$162/sq ft**. Greater Boston builds at
roughly **two times** the national per-square-foot rate, which is why the Suffolk County total
lands near $780,000 rather than the national average. The materials-tax figure scales with it:
at the national average build, materials of ~40–50% imply ~$170,000–$215,000 in materials and
~$10,700–$13,400 in tax; Suffolk County's higher costs roughly double that. This cross-check
confirms the Suffolk County estimate is the right order of magnitude, not an outlier.

## IV. The compounding markup (paired review comment)

A second review comment asked the page to reflect that the contractor's **markup compounds**
the tax. The mechanism, stated precisely:

- Under the contractor-as-consumer rule, the builder pays the 6.25% tax on the materials he
  buys, so the **tax is embedded in his materials cost**.
- A builder prices materials to the owner at **cost plus margin**. Applying the margin to a
  tax-inclusive cost means the **margin is charged on the tax too**.
- Effective tax borne by the owner ≈ **6.25% × (1 + margin)**. At a 20% margin, that is about
  **7.5%**; at a 30% margin, about **8.1%**. The wider the margin, the wider the gap between
  the statutory 6.25% and what the family actually pays.

This is presented on the one-pager qualitatively (with the 20% example) rather than as a
second dollar line, to avoid stacking estimates on estimates; the arithmetic is recorded here.

## V. Before distribution

- Replace the derived range with a **specific, defensible figure** if the coalition can obtain
  actual Suffolk County builder data, or keep the range and cite these sources in a footnote.
- Re-pull the cost-per-square-foot and materials-share inputs for the **most recent** year
  available at the time of use; construction costs have moved sharply since 2022.
- If a fiscal note for the bill becomes available, cite the **statewide** revenue figure
  alongside the per-home figure for completeness.

---

### Sources consulted

- NAHB, *Cost of Constructing a Home — 2024* (avg. ~$428,215 total, ~$162/sq ft; construction = 64.4% of price) — [NAHB](https://www.nahb.org/news-and-economics/housing-economics-plus/special-studies/special-studies-pages/cost-of-constructing-a-home-in-2024); [Eye on Housing](https://eyeonhousing.org/2025/01/cost-of-constructing-a-home-in-2024/); [NAHB blog](https://www.nahb.org/blog/2025/01/cost-of-construction-survey-2024)
- Greater Boston / Massachusetts cost to build per square foot, 2025 — [Houzeo (Boston)](https://www.houzeo.com/blog/how-much-does-it-cost-to-build-a-house-boston-ma/); [Houzeo (MA)](https://www.houzeo.com/blog/how-much-does-it-cost-to-build-a-house-massachusetts/); [HomeGuide](https://homeguide.com/costs/cost-to-build-a-house-in-massachusetts); [Angi (Boston)](https://www.angi.com/articles/how-much-does-it-cost-build-house/ma/boston)
- Average/median size of new single-family homes, 2024 — [Eye on Housing](https://eyeonhousing.org/2025/05/single-family-home-size-trending-higher/); [U.S. Census construction characteristics](https://www.census.gov/construction/chars/highlights.html)
