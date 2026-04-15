# ML Marketing Campaign

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37726.svg)](https://jupyter.org/)
[![codecov](https://codecov.io/gh/mickhornung-oss/ml-marketing-campaign/branch/main/graph/badge.svg)](https://codecov.io/gh/mickhornung-oss/ml-marketing-campaign)
[![Tests](https://github.com/mickhornung-oss/ml-marketing-campaign/actions/workflows/python-tests.yml/badge.svg)](https://github.com/mickhornung-oss/ml-marketing-campaign/actions)[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

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

## ⚡ Quick Start

```bash
# 1. Dependencies installieren
pip install -r requirements.txt

# 2. Notebooks öffnen
jupyter notebook
```

**Notebook-Reihenfolge:**
1. `00_preparation.ipynb` — Datenvorbereitung
2. `00_initial_exploration.ipynb` — Erste Explorationn
3. `01_eda_and_baseline.ipynb` — EDA + Baseline-Modelle
4. `02_churn_analysis.ipynb` — Churn-Vorhersage
5. `03_deal_hunter_analysis.ipynb` — Deal-Jäger erkennen
6. `04_cross_sell_analysis.ipynb` — Cross-Selling-Chancen

✅ Alle Notebooks sind in `notebooks/` organisiert | HTML-Präsentation in `reports/`
