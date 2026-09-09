# Netflix / Warner Bros. Discovery — M&A Model

An M&A / accretion-dilution model simulating a hypothetical acquisition of Warner Bros. Discovery (NASDAQ: WBD) by Netflix (NASDAQ: NFLX). Combines standalone three-statement projections for both companies with a full transaction structure — sources & uses, purchase price allocation, and pro forma accretion/dilution with sensitivity analysis.

**Currency:** USD, millions (except per-share figures)
**Deal / valuation date:** March 23, 2026
**Historical years:** FY2021–FY2025 · **Projection years:** FY2026–FY2030

## Tab guide

| Tab | Purpose |
|---|---|
| **M&A** | Deal control page. Transaction assumptions, offer price/premium, deal structure (% cash / % stock), financing assumptions, sources & uses of funds, purchase price allocation (asset write-ups, goodwill), accretion/dilution summary, and two-way sensitivity tables. |
| **Target Financials** | Warner Bros. Discovery standalone three-statement model (income statement, balance sheet, cash flow statement, working capital schedule), with a circularity breaker switch for interest-driven circular references. |
| **Acquirer Financials** | Netflix standalone three-statement model, same structure and time horizon as Target Financials. |
| **Pro Forma Financials** | Combined company income statement reflecting deal adjustments — synergies, incremental D&A from write-ups, and financing costs. |
| **Shares** | Basic/diluted share count build for both companies, including RSUs/PSUs and treasury-stock-method option dilution. |

## Methodology

Standalone financials → Deal structure → Pro forma combination → Accretion/dilution. The model is fully linked and formula-driven: change an assumption anywhere on the M&A tab and it flows through the purchase price allocation, pro forma statements, and accretion/dilution output.

- **Deal structure:** Offer price of $27.75/share (~1.3% premium), split 50% cash / 50% stock. Cash consideration is financed 80% with new debt and 20% with acquirer excess cash; target debt is refinanced at close.
- **Purchase price allocation:** Target assets and liabilities are written up to fair market value (PP&E and intangibles), generating incremental D&A and deferred tax liabilities, with the residual booked to goodwill.
- **Pro forma combination:** Standalone net income for both companies is combined and adjusted for incremental interest expense on new debt, foregone interest income on cash used, synergies ($4,000M cost / $2,500M revenue annually), and incremental D&A from the write-ups, net of tax.
- **Accretion/dilution:** Pro forma EPS is compared against Netflix's standalone EPS across all five projection years (FY2026–FY2030), with two-way sensitivity tables flexing offer price, % stock consideration, and % of cash financed with debt for years 1–3 post-close.

## Conventions

- Blue text — hardcoded inputs / assumptions
- Black text — formulas
- Green text — links from another sheet
- "Circ Break" toggle on the Target and Acquirer Financials tabs — switches off circular references (enable iterative calculation in Excel if formulas show circular reference warnings)

## How to use

1. Open in Excel (or LibreOffice Calc / Google Sheets).
2. Start on the M&A tab for the headline deal terms and accretion/dilution output.
3. Adjust offer price, consideration mix, financing mix, or synergy assumptions on the M&A tab — everything downstream recalculates automatically.
4. Check the sensitivity tables at the bottom of the M&A tab to see how accretion/dilution moves across offer price, % stock, and % debt financing.

## Disclaimer

This model is a hypothetical modeling exercise for educational and illustrative purposes only. It does not represent an actual, announced, rumored, or endorsed transaction, and none of the assumptions, projections, or outputs should be relied upon for investment or business decisions.
