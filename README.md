# 📚 Amazon Ebook Scraper  

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
