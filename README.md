# 📚 Amazon Ebook Scraper  

## ⚠️ Disclaimer

Ce projet a été réalisé **à des fins purement pédagogiques et personnelles**.  
Il s’agit d’un exercice technique pour apprendre à utiliser **Python** et la librairie **BeautifulSoup** afin de comprendre les bases du parsing HTML et de la collecte de données.

➡️ **Important** :  
- Le scraping de sites comme **Amazon** est **interdit par leurs Conditions Générales d’Utilisation (CGU)**.  
- Ce code n’a pas vocation à être utilisé pour un usage commercial, ni à automatiser la collecte de données réelles sur Amazon.  
- Je décline toute responsabilité en cas d’utilisation abusive de ce projet.  

👉 Si vous souhaitez pratiquer le web scraping, je recommande de vous tourner vers des sites **open data**, des pages web libres de droits, ou des environnements de test prévus pour ça.

---


This project is a simple **web scraping script in Python** that extracts ebook information from Amazon product pages and saves the results into:  
- A **text file** (`scrappEbook-results.txt`)  
- An **Excel file** (`scrappEbook-results.xlsx`)  

It uses `requests`, `BeautifulSoup`, and `openpyxl`.  

---

## 🚀 Features
- Scrapes multiple Amazon product pages in one run.  
- Extracts key ebook details:
  - Title  
  - Author  
  - Rating (stars)  
  - Number of reviews  
  - Publisher  
  - Best Seller Rank  
- Saves results in **Excel** for easy analysis.  
- Also logs details in a **text file** for quick review.  

---

## 🛠️ Requirements
Make sure you have Python 3 installed and the following libraries:  

### install
```bash
pip install requests beautifulsoup4 lxml openpyxl
````

### prepare txt file with URLs
```
https://www.amazon.com/dp/example1; https://www.amazon.com/dp/example2;https://www.amazon.com/dp/example3; etc.
```

---
## ▶️ launch script
```bash
python web-scrapping-script.py
```

---
## 📂 Project structure
```bash
├── scraper.py               # main script (your code)
├── scrappEbook-results.txt  # output (text file)
├── scrappEbook-results.xlsx # output (Excel file)
└── urls.txt                 # file with Amazon product URLs
```
