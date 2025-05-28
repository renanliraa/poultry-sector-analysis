# Poultry Sector Analysis – Programming Challenge

This repository contains a reproducible analysis of Brazilian poultry productivity using data from SIDRA/IBGE (table 7524).

Key takeaways (2013 – 2024):
• The breeder herd has declined ≈ 2 % on a 12-month moving-average basis since 2021.
• Hatching-egg output rebounded +4.3 % YoY in 2024, reversing the drop observed in 2023.
• Productivity reached 7.9 eggs per breeder in the most recent 12-month window – the best performance in the last decade.

Methodological note – quarterly granularity
The SIDRA API delivers these two series at quarterly frequency; monthly requests return 404. To respect the 12-month moving-average metric, each quarter is treated as a three-month block and a 4-quarter rolling window is applied. Consequently, results should be interpreted on a quarterly basis.

Attachments & code access:
1. 12-Month MA – Chicken Breeder Herd (PNG, source: SIDRA/IBGE)
2. YoY Growth – Hatching-Egg Production (PNG, source: SIDRA/IBGE)
3. 12-Month MA – Yield per Breeder (PNG, source: SIDRA/IBGE)
4. Jupyter notebook ProgrammingChallenge_RenanLira.ipynb – fully reproducible (attached)
