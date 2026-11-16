# ASTRA Markets: Should a Grocery Chain Adopt AI Replenishment?

A quantitative decision model built in **Excel Solver**, in five parts.

| Part | Method | Result |
|---|---|---|
| A | Break-even analysis | AI pays off after **12,000** of 45,000 yearly cases (26.7%). At 60% adoption it earns **SAR 180K/yr**. A 20% higher fixed cost moves break-even to 14,400 cases. |
| B | Linear programming (Simplex LP) | Optimal mix: 110 fresh + 26.67 packaged cases a day, for **SAR 7,250/day** |
| C | Sensitivity analysis | Labor shadow price is SAR 3/min. Buying 120 extra minutes for SAR 200 is **worth it (+SAR 160/day)**. Storage is not binding (120 slots spare). |
| D | Nonlinear programming (GRG) | Max profit is **SAR 690.6/day** at f = 21.25, s = 12.5. The best whole-case plan is 22 / 12. |
| E | Decision analysis | Best EMV: full AI (58K). Maximin: pilot at 2 stores (12K). **EVPI = 21.6K**. EVSI = 5K (23% efficiency). |

## Takeaway
If the chain can live with some risk, full AI forecasting has the best expected value. If not, piloting at two stores never loses money. Commissioning a market study (cost 3K) is worth it, because its sample information is worth 5K.

## Files
- [`ASTRA_Markets_Solution.xlsx`](ASTRA_Markets_Solution.xlsx): model, Solver answer and sensitivity reports, decision table

## Skills
Excel Solver · LP formulation · Sensitivity / shadow prices · NLP · Decision trees · EMV, EVPI, EVSI
