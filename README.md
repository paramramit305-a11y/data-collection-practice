# 📘 Data Collection Practice (Web Scraping & APIs)

This repository contains my **hands-on practice of data collection techniques using Python**.  
It covers both **Web Scraping (HTML-based data)** and **Working with APIs (JSON-based data)**, and focuses on converting raw data into **clean, structured datasets** using Pandas.

This work builds a strong foundation for **EDA, Data Analysis, and Machine Learning workflows**.

---

## 📂 Project Structure

---

Data-Collection/
│
├── │ ├── quote1.html
│  Web Scraping/
│ ├── scraped_data/
││ ├── quote2.html
│ │ └── ...
│ │
│ ├── cleaned_data/
│ │ └── life_quotes.csv
│ │
│ └── Scraping_activity.ipynb
│
├── Working With APIs/
│ ├── Practice_APIs.ipynb
│ └── data_collection.ipynb
│
└── README.md

---

## 🕷️ 1️⃣ Web Scraping (HTML → CSV)

### Website Used
- http://quotes.toscrape.com (practice website)

### Workflow
- Sent HTTP requests using `requests`
- Handled pagination using loops
- Saved raw HTML pages locally
- Parsed HTML using `BeautifulSoup`
- Extracted quote text, author, and tags
- Filtered quotes based on the `"life"` tag
- Converted extracted data into a Pandas DataFrame
- Exported cleaned data to CSV

### Output File
cleaned_data/life_quotes.csv

### Dataset Columns
| Column | Description |
|------|------------|
| text | Quote text |
| author | Author name |

- Total **life quotes extracted**: 13  
- Data collected from **multiple paginated pages**

---

## 🌐 2️⃣ Working With APIs (JSON → DataFrame)

### APIs Practiced
- CrossRef API
- Stephen King Books API

### Workflow
- Sent API requests using `requests`
- Parsed JSON responses
- Normalized nested JSON using `pd.json_normalize`
- Selected relevant fields
- Converted API data into structured Pandas DataFrames

### Example Fields Extracted
- Publisher
- Type
- Page range
- Publication year
- Book title
- ISBN

---

## 🛠️ Tools & Libraries Used

- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- Jupyter Notebook

---

## 🎯 Learning Outcomes

Through this repository, I practiced:
- Data collection from **web pages and public APIs**
- Pagination handling
- HTML parsing
- JSON normalization
- Data cleaning and structuring
- Preparing datasets for EDA and ML pipelines

This repository reflects my **step-by-step learning approach** toward **Data Science & AI Engineering fundamentals**.

---

## 📌 Notes
- All websites and APIs used are public and learning-friendly
- This project is for **educational purposes only**

---

## 🚀 Future Improvements
- Advanced EDA
- Data visualization
- Text preprocessing (NLP basics)
- Feature engineering

---

## 👤 Maintained By
**Amit Parmar**  
Learning-focused repository documenting structured progress in data collection and analysis.
