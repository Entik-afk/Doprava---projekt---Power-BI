# Logistická analýza v Power BI (2023–2025)

Interaktivní Power BI dashboard pro analýzu zásilek, přepravců a časů doručení.

## Obsah
- **Executive Overview** — celkový výkon, YoY srovnání, složení přepravy
- **Analýza přepravců** — porovnání ceny, rychlosti a efektivity 17 přepravců
- **Operativní monitor** — outlier detekce, rozložení doby přepravy, heatmapa

## Klíčové DAX míry
- Index efektivity — normalizované skóre přepravce (cena 60 %, rychlost 40 %)
- RANKX — rank přepravců podle průměrné ceny na kg
- Outlier detekce — kalibrovaná per typ přepravy (Sea, Air, Express...)
- YoY srovnání — SELECTEDVALUE + FILTER pro robustní meziroční porovnání

## Technologie
Power BI Desktop · DAX · Custom theme JSON
