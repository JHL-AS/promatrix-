# ProMatrix

**One of the most powerful matrix for Microsoft Power BI — finance-ready out of the box.**

ProMatrix is an advanced, flexible matrix custom visual for Power BI. Build profit & loss
statements, balance sheets, budget variance and **any structured report** — with the layout control
of Excel and the interactivity of Power BI. No reshaping of data and no DAX required for report logic.

🔗 **Product & pricing:** https://jhl.no/promatrix.html  ·  **Docs:** https://jhl.no/promatrix-hjelp.html

> This repository published for transparency and Microsoft Power BI
> certification review. It is **not** open source — see [LICENSE](LICENSE).

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

Proprietary, source-available. © 2026 JHL AS. All rights reserved. See [LICENSE](LICENSE).
Third-party components (e.g. ExcelJS, MIT) retain their own licenses.

## Support

JHL AS · post@jhl.no · https://jhl.no
