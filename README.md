# Sales analysis: data cleaning and findings

🇪🇸 [Leer en español](README.es.md)

Full cleaning and analysis of a 4,215-record sales dataset (2024-2025)
with typical export issues: numeric columns stored as text, inconsistent
categories, dates in three different formats, and impossible values.

## Results

- **Corrected a 1,200% error** in the units-per-transaction metric (40.3
  recorded vs. 3.0 real). Any report built without prior cleaning would
  have reported that figure.
- **Detected a discount policy not justified by volume:** the wholesale
  channel runs a flat 18% discount and buys 3.03 units per transaction,
  versus 3.01 in retail channels.

## Contents

| File | Description |
|---|---|
| `limpieza_ventas.ipynb` | Notebook with the full process and findings |
| `ventas_sucio.csv` | Raw data |
| `ventas_limpio.csv` | Cleaned dataset |

## Tools

Python · pandas · matplotlib

---

*Simulated dataset with quality issues representative of real-world exports.*
