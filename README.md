# Inventory Replenishment Agent

EWMA-forecast, safety-stock-based replenishment agent with a day-by-day simulator, daily decision log, and comparison against a fixed (s,Q) baseline.

## Run
```
pip install -r requirements.txt
jupyter notebook InventoryReplenishmentAgent.ipynb   # Run All
```
If `sales.csv`, `inventory.csv`, `params.csv` are missing, the notebook generates them (3 SKUs, 120 days, seed 42).

## Files
- `InventoryReplenishmentAgent.ipynb` – code
- `ScalingNote` - Scaling notes
- `Design_document` -  daily log, evaluation, trade-offs
- `sales.csv`, `inventory.csv`, `params.csv` – input data
- `agent_daily_log.csv` – per-day, per-SKU decisions with rationale (output)
