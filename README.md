# ML Marketing Campaign

Machine-Learning-Projekt zur Analyse einer Marketingkampagne mit Fokus auf **Churn-Vorhersage**, **Deal-Jäger-Erkennung** und **Cross-Selling-Potenzial**.

## Ziel
Dieses Projekt untersucht, welche Kundengruppen besonders wertvoll, abwanderungsgefährdet oder stark rabattgetrieben sind. Ziel ist es, Marketingmaßnahmen datenbasiert zu priorisieren und Budgets gezielter einzusetzen.

## Inhalte
- Explorative Datenanalyse auf Basis von `Marktkampagne.csv`
- Mehrere Jupyter Notebooks für unterschiedliche Fragestellungen
- Präsentation als PowerPoint und HTML-Version
- Aufgabenstellung als PDF

## Projektstruktur
```text
ml-marketing-campaign/
├── data/
│   └── Marktkampagne.csv
├── notebooks/
│   ├── 00_preparation.ipynb
│   ├── 00_initial_exploration.ipynb
│   ├── 01_eda_and_baseline.ipynb
│   ├── 02_churn_analysis.ipynb
│   ├── 03_deal_hunter_analysis.ipynb
│   └── 04_cross_sell_analysis.ipynb
├── reports/
│   ├── marketing-campaign-presentation.pptx
│   ├── marketing-campaign-presentation.html
│   └── project-brief.pdf
├── images/
│   ├── campaign-visual-01.jpg
│   └── campaign-visual-02.jpg
├── requirements.txt
└── README.md
```

## Verwendete Technologien
- Python
- pandas
- scikit-learn
- Jupyter Notebook
- matplotlib

## Erkenntnisinteresse
- Welche Kunden zeigen erhöhtes Churn-Risiko?
- Welche Kunden reagieren besonders stark auf Rabatte?
- Wo bestehen Cross-Selling-Chancen?

## Ausführung
```bash
pip install -r requirements.txt
jupyter notebook
```
Notebook-Reihenfolge: Beginne mit den `00_*`-Notebooks zur Vorbereitung, dann folge den nummerierten Analyseschritten zum Verständnis der ML-Modelle.
