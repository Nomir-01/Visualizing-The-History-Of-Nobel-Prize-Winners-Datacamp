# Visualizing the History of Nobel Prize Winners

An exploratory analysis of Nobel Prize laureates that examines representation across gender, birth country, decade, and award category. The notebook also identifies the first female laureate and recipients who have won more than once.

## Analysis questions

- Which gender and birth country appear most frequently among laureates?
- Which decade has the highest proportion of US-born winners?
- Which decade and category have the highest proportion of female laureates?
- Who was the first female Nobel Prize winner, and in which category?
- Which individuals have received multiple Nobel Prizes?

## Tools

- Python
- pandas and NumPy
- Seaborn
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — data preparation, aggregation, and visual analysis
- `data/` — Nobel Prize laureate dataset
- `Nobel_Prize.png` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

Run the notebook from the repository root so its relative path to `data/` is preserved.

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates grouping, ratios, categorical analysis, chronological filtering, and data visualization with pandas and Seaborn.
