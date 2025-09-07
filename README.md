# Natural Language Processing - Yelp Review Classification

Dieses Projekt demonstriert die Klassifizierung von Yelp-Bewertungen in 1-Sterne oder 5-Sterne Kategorien mithilfe von Natural Language Processing und Machine Learning.

## Inhalt

- **3-Nlp_Projekt.ipynb**: Hauptnotebook mit dem kompletten NLP-Workflow
- **Yelp.csv**: Datensatz mit Yelp-Bewertungen
- **requirements.txt**: Python-Abhängigkeiten
- **environment.yml**: Conda-Umgebung für Binder

## Binder Launch

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jnooo-cloud/natural-language-processing/HEAD)


## Lokale Installation

```bash
pip install -r requirements.txt
jupyter notebook 3-Nlp_Projekt.ipynb
```

## Features

- Exploratory Data Analysis (EDA) der Yelp-Bewertungen
- Text-Preprocessing mit CountVectorizer
- Naive Bayes Klassifizierung
- TF-IDF Transformation mit Pipeline
- Performance-Evaluation mit Confusion Matrix und Classification Report
