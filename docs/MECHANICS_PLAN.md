# Ticarium Mechanics Plan

Workspace for game mechanics, structured data and spreadsheet calculations.

## Work sequence
1. Products: stable IDs, categories, units and icons.
2. Materials: acquisition methods and costs.
3. Recipes: input quantities, batch output, time and yield.
4. Production costs: materials, labour, energy, transport, overhead and fees.
5. Quality levels: observed selling prices and product-specific multipliers.
6. Businesses: construction, upgrades, capacity, storage and upkeep.
7. Markets: supply, demand, prices and fees.
8. Accounts: sources of money, transfers and financial rules.
9. Functions: unlocks, timers, limits, rewards and dependencies.
10. Spreadsheet validation and balance scenarios.

## Evidence
Mark values as verified, observed, estimated, proposed or unknown. Record source, observation date, units, currency and game version when known. Separate observed Ticarium behaviour from proposed rules for our own game. No game values have been imported in this document.

## Proposed accounting formulas
- Material batch cost = sum(input quantity * unit price).
- Total batch cost = materials + labour + energy + transport + allocated overhead + production fees.
- Unit production cost = total batch cost / saleable output; flag zero output.
- Net sales = gross sales - selling fees - taxes.
- Profit = net sales - production cost of units sold.
- Quality multiplier = observed quality price / baseline-quality price for the same product under comparable conditions.

These formulas are proposed accounting models, not verified Ticarium rules. Document rounding, units and fee bases. Inspect existing workbooks before importing data.
