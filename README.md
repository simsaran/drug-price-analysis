# drug-price-analysis
# The Real Cost of Getting Better
### A Comparative Analysis of Drug Prices Across Canada, USA, UK, and India

---

I picked up a prescription recently and paid more than I expected for a drug that has been off patent for over a decade. Out of curiosity I looked up what the same medication costs in other countries. The differences were significant enough that I decided to investigate properly.

I have a biochemistry and bioinformatics degree from the University of Waterloo and spent time in vaccine formulation labs at Sanofi. I understand how drugs are developed and approved. What I wanted to understand was why the same molecule, at the same dose, from the same manufacturer, costs a different amount depending on which country you happen to live in.

The answer is not the science. The price is determined by regulation, negotiation, and market structure.

---

## Key findings

| Finding | Detail |
|---------|--------|
| Canada vs UK | Canadian patients pay an average of 2.7x more than UK NHS patients for the same drugs |
| Canada vs India | Canadian patients pay an average of 4.6x more than Indian patients |
| Canada vs USA | Canada is actually cheaper, Canadian prices average 3.1x less than US cash prices |
| Most extreme case | Salbutamol inhaler, 29.7x price difference between cheapest and most expensive country |
| Annual gap (uninsured) | An uninsured Ontario resident pays approximately $2,324 more per year than a UK NHS patient for the 10 drugs in this sample |
| Generic drugs | 8 of 10 drugs in this sample are off patent, but off patent does not mean affordable everywhere |

---

## What is in this repo

| File | What it contains |
|------|-----------------|
| drug-price-dataset.csv | 10 drugs with prices in 4 countries, regulatory body, pricing mechanism, patent status, and data sources |
| price-ratio-analysis.csv | Price ratios, annual costs, and savings calculations for each drug |
| regulatory-comparison.csv | Full regulatory framework comparison across Canada, USA, UK, and India |
| patient-impact.csv | Annual out-of-pocket cost for an uninsured Ontario resident vs NHS patient |
| analysis-summary.csv | All headline numbers in one place |
| drug-price-analysis.xlsx | Excel workbook with 3 sheets — price comparison, regulatory comparison, patient impact |
| analysis-report.pdf | Full briefing note style report with methodology, findings, and regulatory framework explanation |

---

## Data sources

All prices are from publicly available official sources. No estimates were used.

| Country | Source | URL |
|---------|--------|-----|
| Canada | Ontario Drug Benefit Formulary | health.gov.on.ca |
| USA | GoodRx cash price | goodrx.com |
| UK | NHS Drug Tariff | nhsbsa.nhs.uk |
| India | NPPA drug price database | nppaindia.nic.in |

Exchange rates as of May 2026. Prices represent standard 30-day supply at most commonly prescribed dose.

---

## The 10 drugs analysed

| Drug | Category | Patent status |
|------|----------|--------------|
| Metformin 500mg | Diabetes | Off patent |
| Semaglutide 0.5mg (Ozempic) | Diabetes | On patent until 2031 |
| Atorvastatin 40mg | Cardiovascular | Off patent |
| Rosuvastatin 10mg | Cardiovascular | Off patent |
| Ramipril 10mg | Cardiovascular | Off patent |
| Salbutamol 100mcg inhaler | Respiratory | Off patent |
| Montelukast 10mg | Respiratory | Off patent |
| Sertraline 50mg | Mental Health | Off patent |
| Duloxetine 60mg | Mental Health | Off patent |
| Amoxicillin 500mg | Infectious Disease | Off patent |

---

## Skills demonstrated

Pharmaceutical regulatory knowledge across 4 jurisdictions. Public database research and data validation. Multi-source data collection and standardisation. Price ratio and gap analysis. Patient impact modelling. Regulatory framework comparison. Briefing note writing in health economics style. Excel financial modelling with conditional formatting. Looker Studio dashboard design. Cross-functional thinking connecting science, regulation, economics, and patient outcomes.

---

## About this project

This is part of a portfolio series built while job searching in Canada after graduating from the University of Waterloo.

Prepared by Simran Saran. Background in biochemistry, bioinformatics, and pharmaceutical lab experience. Targeting roles in regulatory affairs, business analysis, and associate scientist positions across Canada.

This analysis is intended for educational and portfolio purposes. All data is publicly available. Prices are a point-in-time snapshot and subject to change.
