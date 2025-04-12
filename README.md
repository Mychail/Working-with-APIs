# 🌍 Wikipedia API Data Project

This repository contains tools and scripts for extracting, analyzing, and visualizing data from Wikipedia using Python. The focus is on population data and billionaire statistics scraped or retrieved via Wikipedia APIs or direct HTML parsing.

---

## 📁 Project Structure

| File / Folder                 | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| `countries_population.csv`   | Cleaned CSV of country population data extracted from Wikipedia             |
| `index.html`                 | HTML snapshot or scraped source of the Wikipedia population page            |
| `wiki_billionaire_api_EDA.ipynb` | Jupyter Notebook exploring billionaire data using Wikipedia API             |
| `README.md`                  | This project documentation                                                  |
| `.gitignore`                 | Git ignore file to exclude unnecessary files                                |

---

## 🧠 Project Highlights

- ✅ **API + Web Scraping** from Wikipedia  
- 📊 **Exploratory Data Analysis (EDA)** on global population and billionaire lists  
- 📥 **Data Saved** in clean, shareable CSV format  
- 🧹 Built-in data cleaning and parsing logic  
- 📈 Visualization-ready outputs for Kaggle or data storytelling

---

## 📦 Requirements

- Python 3.8+
- `pandas`
- `wikipedia-api` or `requests + BeautifulSoup`
- `jupyter` (for `.ipynb` notebook)

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Extract & Save Population Data
```bash
python src/extract_population.py
```

### Run EDA Notebook
Open `wiki_billionaire_api_EDA.ipynb` in Jupyter to explore insights.

---

## 📚 Data Sources

- [Wikipedia: List of countries and dependencies by population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population)
- [Wikipedia API documentation](https://pypi.org/project/Wikipedia-API/)

---

## 📌 Notes

- Dataset is intended for educational and exploratory use.
- May require refreshing periodically for up-to-date population figures.

---

## 🤝 Contributing

Feel free to fork, open issues, or suggest improvements via pull requests.

---

## 🪪 License

This project is licensed under the MIT License.
