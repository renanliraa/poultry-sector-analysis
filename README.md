# Poultry Sector Analysis 

This repository contains a reproducible analysis of Brazilian poultry productivity using data from SIDRA/IBGE (table 7524).

Key takeaways (2013 – 2024):
• The breeder herd has declined ≈ 2 % on a 12-month moving-average basis since 2021.
• Hatching-egg output rebounded +4.3 % YoY in 2024, reversing the drop observed in 2023.
• Productivity reached 7.9 eggs per breeder in the most recent 12-month window – the best performance in the last decade.

Methodological note – quarterly granularity
The SIDRA API delivers these two series at quarterly frequency; monthly requests return 404. To respect the 12-month moving-average metric, each quarter is treated as a three-month block and a 4-quarter rolling window is applied. Consequently, results should be interpreted on a quarterly basis.

