# Kunskapskontroll 1: Analys av FIFA World Cup 2026 (Simulering)

Detta projekt är en del av kursen **Artificiell Intelligens – programmering Python (MAI25MA)**. Syftet är att demonstrera färdigheter i dataanalys med Pandas, Numpy och visualisering med Matplotlib.

## Projektbeskrivning
Analysen fokuserar på det utökade formatet av FIFA World Cup 2026 (48 lag). Datasetet innehåller statistik över lagens prestationer de senaste fyra åren, tidigare VM-meriter och truppstyrka.

### Frågeställningar
* Hur ser fördelningen av lag ut mellan de olika kontinenterna i det nya formatet?
* Finns det ett samband mellan historisk erfarenhet och nuvarande målproduktion?
* Vilka kontinenter förväntas dominera baserat på statistik från de senaste fyra åren?

## Dataset
* **Källa:** [Kaggle - FIFA World Cup Team Dataset](https://www.kaggle.com/datasets/harrachimustapha/fifa-world-cup-team-dataset)
* **Omfattning:** 48 lag, 24 statistiska variabler per lag.

## Struktur
* `notebook.ipynb`: Huvudanalysen och visualiseringarna.
* `data/`: Innehåller rådatan i CSV-format.

## Installation
För att köra notebooken lokalt:
1. Klona repot.
2. Skapa en virtuell miljö: `python -m venv .venv`
3. Installera bibliotek: `pip install pandas numpy matplotlib seaborn kagglehub`