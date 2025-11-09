#  Airbnb Datenanalyse – Explorative Analyse & Präsentation

Dieses Projekt analysiert einen Airbnb-Datensatz (ca. 51.000 Einträge) im Rahmen meiner beruflichen Weiterbildung zum **Data Analyst**.  
Ziel war es, von der Datenbereinigung über Visualisierung bis hin zur Präsentation einen vollständigen Analyse-Workflow umzusetzen.

---

##  Projektziele

- Daten laden, bereinigen und ausreißerbereinigt analysieren
- Explorative Datenanalyse (EDA) mit Visualisierungen
- Erkenntnisse zu:
  - Superhosts vs. normale Hosts (Preis & Umsatz)
  - Zimmer-Typen (room_type)
  - Gästeanzahl (person_capacity)
  - Schlafzimmern (bedrooms)
  - Cleanliness-Rating (cleanliness_rating)
- Ergebnisse in einer **PowerPoint-Präsentation** zusammengefasst

---

##  Projektstruktur

| Datei | Beschreibung |
|-------|--------------|
| `projektanalyse3.ipynb` | Jupyter Notebook mit der kompletten Analyse, Visualisierungen & Code |
| `README.md` | Projektbeschreibung (du liest sie gerade 😊) |
| *(Optional)* PowerPoint Präsentation | **entfernt**, da Dateigröße zu groß für GitHub war |

---

## 🔧 Technologien

| Tool / Bibliothek | Zweck |
|------------------|-------|
| **Python 3.12** | Hauptsprache |
| `pandas` | Datenbereinigung & Analyse |
| `matplotlib`, `seaborn` | Visualisierung |
| `numpy` | numerische Operationen |
| `Jupyter Notebook` | Schrittweise Analyse & Dokumentation |

---

##  Vorgehensweise

1. **Datenbereinigung**
   - Entfernen von fehlerhaften Werten
   - Markieren von Ausreißern (nicht gelöscht!)
   - Vereinheitlichung von Spalten

2. **EDA (Explorative Datenanalyse)**
   - Histogramme → Verteilungsanalyse
   - Boxplots → Ausreißeranalyse
   - Heatmaps → Korrelationen

3. **Business Insights**
   - Wie viel verdienen Superhosts im Vergleich zu normalen Hosts?
   - Bringt mehr Kapazität (mehr Zimmer / mehr Gäste) auch mehr Umsatz?

4. **Dokumentation**
   - Alle Ergebnisse im Notebook + Präsentation

---

##  Beispiel-Insights (kurzfassung)

- Superhosts verdienen im Durchschnitt **mehr** als normale Hosts
- Zimmer-Typ *Entire Home / Apartment* erzeugt den größten Umsatz
- Mehr Zimmer = höhere Preisbereitschaft der Gäste
- Höhere Sauberkeitsbewertung → tendenziell bessere Buchungsrate

> Alle Details inkl. Diagrammen findest du im Notebook.

---

## ▶️ Wie du das Notebook öffnen kannst

**Variante 1: Direkt im Browser**
1. Datei `projektanalyse3.ipynb` im Repo anklicken
2. GitHub zeigt eine Vorschau an

**Variante 2: Lokal ausführen**

git clone https://github.com/Stavros2410/airbnb-analysis.git
cd airbnb-analysis
jupyter notebook



