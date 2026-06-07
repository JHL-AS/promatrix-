# ProMatrix

**One of the most powerful matrix for Microsoft Power BI — finance-ready out of the box.**

ProMatrix is an advanced, flexible matrix custom visual for Power BI. Build profit & loss
statements, balance sheets, budget variance and **any structured report** — with the layout control
of Excel and the interactivity of Power BI. No reshaping of data and no DAX required for report logic.

🔗 **Product & pricing:** https://jhl.no/promatrix.html  ·  **Docs:** https://jhl.no/promatrix-hjelp.html

> This repository hosts the packaged ProMatrix visual and its documentation. The readable
> source code is **not** published here. ProMatrix is a commercial, proprietary product — see
> [LICENSE](LICENSE).

---

## Highlights

- **Report templates out of the box** — IFRS, Norway (GRS, NS 4102), Sweden (BAS), Germany (SKR04),
  Denmark, Finland — income statement & balance sheet, or build your own.
- **Smart auto-build** — detects your chart of accounts and builds the matching statement, with
  automatic sign handling for negatively-stored costs.
- **Visual report editor** — sum, formula and result lines, cross-references within the statement,
  hide/show rows — no JSON required.
- **Excel-style formula engine** (no DAX) — `IF`, `GROWTH`, `ABS`, `ROUND`, `MIN/MAX`, `AVERAGE`,
  `SUM`, comparisons; division by zero renders blank.
- **Calculated columns & sparklines** — variance, %, ratios, period-over-period, per group.
- **Conditional formatting** — sign, color scale, data bars, icons, variance, centered variance bars.
- **One-click IBCS** (light / purist) with automatic Δ / Δ% variance columns.
- **Display & analysis** — show values as % of total / parent row, Top/Bottom-N with an "Other" row,
  value bar in the row header, group totals top/bottom, fixed/auto column widths, freeze columns.
- **Excel export** — real `.xlsx` with formatting and hierarchy preserved.
- **Multilingual UI** (10 languages), high contrast, keyboard navigation.

## Full feature list

| Feature | Free | Pro | Premium | Enterprise |
|---|:--:|:--:|:--:|:--:|
| **Matrix & core** | | | | |
| Hierarchical matrix with subtotals & grand totals | ✓ | ✓ | ✓ | ✓ |
| Expand/collapse on rows and columns | ✓ | ✓ | ✓ | ✓ |
| Frozen row and column headers | ✓ | ✓ | ✓ | ✓ |
| Sorting, search, hide empty rows/columns | ✓ | ✓ | ✓ | ✓ |
| Cross-filtering & highlighting | ✓ | ✓ | ✓ | ✓ |
| Click filter: whole row or single cell | ✓ | ✓ | ✓ | ✓ |
| Number format (decimals, separators, culture) | ✓ | ✓ | ✓ | ✓ |
| Per-column styling (color, width, align, hide) | ✓ | ✓ | ✓ | ✓ |
| Style system (Header / Subtotal / Total / Emphasis) | ✓ | ✓ | ✓ | ✓ |
| Multilingual UI (10 languages), high contrast, keyboard | ✓ | ✓ | ✓ | ✓ |
| **Reporting & finance** | | | | |
| Templates: IFRS, GRS, NS 4102, BAS, SKR04, DK, FI | ✓ | ✓ | ✓ | ✓ |
| Visual report editor (sum/formula/result) | ✓ | ✓ | ✓ | ✓ |
| Smart auto-build (chart-of-accounts detection) | ✓ | ✓ | ✓ | ✓ |
| Automatic sign handling (negative costs) | ✓ | ✓ | ✓ | ✓ |
| Formulas in row lines (IF, GROWTH, ABS, ROUND …) | ✓ | ✓ | ✓ | ✓ |
| Cross-references within the statement (P&L → balance) | ✓ | ✓ | ✓ | ✓ |
| Comments (data-driven + notes) | ✓ | ✓ | ✓ | ✓ |
| Sign colors (conditional) | ✓ | ✓ | ✓ | ✓ |
| **Display & analysis** | | | | |
| Show values as % (of column total / parent row) | ✓ | ✓ | ✓ | ✓ |
| Top/Bottom-N with an aggregated "Other" row | ✓ | ✓ | ✓ | ✓ |
| Hide rows below a threshold (0 / amount) | ✓ | ✓ | ✓ | ✓ |
| Hide individual rows (still counts in sums) | ✓ | ✓ | ✓ | ✓ |
| Value bar in the row header (visual weight) | ✓ | ✓ | ✓ | ✓ |
| Group total at top or bottom | ✓ | ✓ | ✓ | ✓ |
| Fixed row-header width + freeze first N columns | ✓ | ✓ | ✓ | ✓ |
| Unit caption + "–" on selected rows | ✓ | ✓ | ✓ | ✓ |
| Division by zero → blank (no misleading 0) | ✓ | ✓ | ✓ | ✓ |
| Drill-through / "see transactions" (right-click) | ✓ | ✓ | ✓ | ✓ |
| **Pro features** | | | | |
| Without "ProMatrix by jhl.no" mark | – | ✓ | ✓ | ✓ |
| Excel export (all / as shown / top level) | – | ✓ | ✓ | ✓ |
| Calculated columns & sparklines (per group) | – | ✓ | ✓ | ✓ |
| Advanced conditional formatting (scale, bars, icons) | – | ✓ | ✓ | ✓ |
| Variance analysis + IBCS style (light/purist, auto-Δ) | – | ✓ | ✓ | ✓ |
| Compare columns Δ / Δ% (vs budget / prior year) | – | ✓ | ✓ | ✓ |
| Show numbers without sign (magnitude) | – | ✓ | ✓ | ✓ |
| Inline subtotals (Σ overlay) | – | ✓ | ✓ | ✓ |
| **Premium features** | | | | |
| Values on rows (measure placement) | – | – | ✓ | ✓ |
| Group: multiple companies on one license | – | – | ✓ | ✓ |
| **Enterprise** | | | | |
| White-label (remove all branding) | – | – | – | ✓ |
| Custom templates & onboarding | – | – | – | ✓ |
| Partner/reseller & multiple tenants | – | – | – | ✓ |
| SLA & priority support | – | – | – | ✓ |
| Volume & framework agreements, invoicing | – | – | – | ✓ |
| **Size** | 250 rows · 12 cols | 1,500 · 40 | Unlimited | Unlimited |

## Privacy & certification

ProMatrix runs **100% inside the Power BI visual sandbox** and makes **no external network calls**.
Your data never leaves Power BI through the visual. Licensing is verified **offline** (ECDSA P-256 via
`crypto.subtle`) — there is no telemetry, login, or cloud dependency. This makes the visual eligible
for Microsoft certification and suitable for environments with strict data requirements.

## Install

- **From AppSource:** Power BI → *Get more visuals* → search “ProMatrix”.
- **Sideload:** download the latest `.pbiviz` and use *… → Import a visual from a file*.

## Licensing model

ProMatrix is a commercial product with a free tier:

| | Free | Pro | Premium | Enterprise |
|---|---|---|---|---|
| Scope | Get started | One company | Group | Tailored |
| Size | 250 rows · 12 cols | 1,500 · 40 | Unlimited | Unlimited |

See https://jhl.no/promatrix.html#priser for current pricing.

## License

Proprietary. © 2026 JHL AS. All rights reserved. See [LICENSE](LICENSE).
The packaged visual is licensed to end users under the EULA at https://jhl.no/terms.html.

## Support

JHL AS · post@jhl.no · https://jhl.no
