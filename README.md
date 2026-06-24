# 🌐 CodeAlpha Task 1 - Web Scraping using Python

## 📌 Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The objective of this project is to perform **web scraping** using Python by extracting quotes, authors, and tags from the website **Quotes to Scrape** and storing the extracted data in a structured CSV file.

---

## 🎯 Objective

- Learn the fundamentals of web scraping.
- Extract data from a website automatically.
- Store the extracted data in a structured format.
- Create a reusable dataset for further analysis.

---

## 🌍 Website Used

**Quotes to Scrape**

http://quotes.toscrape.com

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Requests
- BeautifulSoup (bs4)
- Pandas

---

## 📚 Libraries Used

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
```

---

## 🔄 Project Workflow

1. Install required libraries.
2. Import the libraries.
3. Connect to the website using Requests.
4. Parse the HTML using BeautifulSoup.
5. Extract:
   - Quote Text
   - Author Name
   - Tags
6. Store the extracted data in Python lists.
7. Create a Pandas DataFrame.
8. Save the data as a CSV file.

---

## 📂 Files Included

- task1.ipynb
- quotes_dataset.csv
- README.md

---

## 📊 Output

The extracted dataset contains the following columns:

| Column | Description |
|---------|-------------|
| Quote | Quote text |
| Author | Name of the author |
| Tags | Tags associated with the quote |

---

## 📈 Skills Demonstrated

- Web Scraping
- HTML Parsing
- Data Collection
- Data Cleaning
- Data Storage using Pandas
- CSV File Generation

---

## 🎓 Learning Outcomes

Through this project, I learned:

- How web scraping works.
- How HTTP requests are sent using Requests.
- How BeautifulSoup parses HTML.
- How to locate HTML elements using tags and classes.
- How to organize scraped data using Pandas.
- How to export data to CSV format.

---

## 🚀 Future Improvements

- Scrape multiple pages instead of a single page.
- Add exception handling.
- Automate data collection.
- Export data to Excel and SQL database.
- Schedule scraping at regular intervals.

---

## 👩‍💻 Author

**Ramya Moorthy**

CodeAlpha Data Analytics Intern
