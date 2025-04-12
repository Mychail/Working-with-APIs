
# 🌐 Wikipedia API Data Extractor

This repository contains Python scripts that extract structured data from the [Wikipedia page on countries and dependencies by population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population) using the `wikipedia-api` and `pandas` libraries. The data is cleaned, transformed, and saved for further analysis or integration into data pipelines.

---

## 📁 Project Structure

```
📦 wikipedia-api-data
├── data/
│   └── countries_population.csv
├── src/
│   └── extract_population.py
├── README.md
└── requirements.txt
```

---

## 🚀 Features

- Extracts population tables from Wikipedia using BeautifulSoup or Wikipedia API
- Parses and tags data by year if applicable
- Converts HTML tables into clean CSV format
- Handles edge cases in HTML structure gracefully

---

## 🧰 Technologies Used

- Python 3.x  
- `pandas`  
- `requests`  
- `wikipedia-api` or `BeautifulSoup`  
- `lxml`  

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/wikipedia-api-data.git
cd wikipedia-api-data
pip install -r requirements.txt
```

---

## 🧪 Usage

Run the extraction script:

```bash
python src/extract_population.py
```

This will generate a CSV file (e.g., `countries_population.csv`) in the `data/` folder.

---

## 📊 Sample Output

A sample of the output CSV file looks like this:

| Country                | Population     | Year |
|------------------------|----------------|------|
| India                  | 1,428,627,663   | 2025 |
| China                  | 1,425,671,352   | 2025 |
| United States          | 339,996,563     | 2025 |
| ...                    | ...             | ...  |

---

## 📌 Notes

- Data was sourced from the Wikipedia page:  
  [List of countries and dependencies by population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population)
- Consider validating population figures for long-term use cases with official sources (e.g., UN or World Bank).

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.
