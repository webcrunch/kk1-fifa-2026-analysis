# Kunskapskontroll 1: Analys av FIFA World Cup 2026 (Simulering)

Detta projekt är en del av kursen **Artificiell Intelligens – programmering Python (MAI25MA)** vid NBI Handelsakademin. Syftet är att demonstrera färdigheter i dataanalys med biblioteken Pandas och Numpy, samt avancerad visualisering med Matplotlib och Seaborn.

## Projektbeskrivning
Analysen fokuserar på det utökade formatet av FIFA World Cup 2026 (48 lag). Genom att kombinera historisk statistik, ekonomisk data från transfermarknaden och spelarspecifik information, skapas en datadriven helhetsbild av den moderna fotbollens maktbalans inför mästerskapet.

### Dimensioner i Analysen
Projektet är uppbyggt kring fem analytiska dimensioner för att utforska vad som bygger ett framgångsrikt landslag:

1. **Den ekonomiska dimensionen:** Vilka nationer har de mest värdefulla spelartrupperna och hur ser fördelningen ut?
2. **Den mänskliga dimensionen:** Analys av åldersstrukturen och "generationsgapet" mellan unga talanger och erfarna veteraner i relation till medianåldern.
3. **Den strukturella dimensionen:** Vilka ligor och kontinenter dominerar som bas för landslagsspelarna? Inkluderar även analys av målproduktion per kontinent via boxplots.
4. **Den statistiska validiteten (ROI):** Sambandet mellan ett lags marknadsvärde och deras faktiska prestationer (vinster). Identifiering av effektiva lag kontra underpresterare via kvadrantanalys.
5. **Den historiska dimensionen:** Hur stor är den statistiska fördelen av att spela på hemmaplan baserat på data från 2002–2024?

## Dataset
Projektet integrerar flera dataset från Kaggle för att skapa en djupgående analys:
* **FIFA World Cup Team Dataset:**
    * `fifa_history`: Historisk statistik från tidigare VM-turneringar.
    * `fifa_2026`: Statistisk simulering och aktuell form för de förväntade 48 lagen.
* **Football Transfer Market Dataset:**
    * `players`: Detaljerad demografisk information om spelare globalt.
    * `transfermarkt`: Ekonomisk data och marknadsvärden för spelare och landslag.

## Struktur
* `final_fifa.ipynb`: Jupyter Notebook som innehåller hela analysen, datatvätt och samtliga visualiseringar.
* `data/`: Innehåller rådatan i CSV-format (krävs för att köra notebooken).
* `README.md`: Översikt och dokumentation av projektet.

## Installation & Användning
För att köra notebooken lokalt krävs Python 3.x och följande bibliotek:

1. **Klona repot** eller ladda ner filerna.
2. **Skapa en virtuell miljö:**
   ```bash
   python -m venv .venv
   ```

3. Aktivera miljön:

- Windows: .venv\Scripts\activate

- Mac/Linux: source .venv/bin/activate

4. Installera nödvändiga bibliotek:

  ```bash
    pip install pandas numpy matplotlib seaborn
   ```

5. Starta Jupyter:

```bash
jupyter notebook final_fifa.ipynb   

```

### Begränsningar och Datavaliditet
Analysen tar hänsyn till att historisk data sträcker sig från 2002. En kritisk del av projektet har varit hanteringen av "Missing Values", särskilt rörande spelare utan ligatillhörighet, vilket redovisas öppet i rapporten för att säkerställa hög validitet.

Utvecklat av Jarl Lindquist - 2026