# 🚗 Cars24 Used Cars Web Scraping & Data Extraction

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Selenium](https://img.shields.io/badge/Selenium-Web_Automation-green?logo=selenium)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web_Scraping-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458?logo=pandas)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📖 Overview

This project automates the collection of used car listings from the **Cars24** website using **Selenium** and **BeautifulSoup**. It extracts vehicle details from multiple city listings, performs data cleaning, and prepares a structured dataset for further analysis and machine learning applications.

The scraper simulates browser interactions to load dynamic content, parses the webpage, and extracts key vehicle information into a consolidated dataset.

---

# 🎯 Objectives

- Automate the scraping of Cars24 used car listings.
- Collect data from multiple cities.
- Extract important vehicle attributes.
- Clean and preprocess the scraped data.
- Create a structured dataset for analysis.
- Build a reusable scraping pipeline.

---

# 🌍 Cities Covered

- Delhi NCR
- Bangalore
- Hyderabad
- Chennai
- Ahmedabad
- Gurgaon
- Mumbai
- Pune

---

# 📊 Features Extracted

The scraper collects the following information for each vehicle:

| Feature | Description |
|----------|-------------|
| Car Name | Vehicle model name |
| Variant | Vehicle variant |
| Price | Selling price |
| EMI Per Month | Estimated monthly EMI |
| Driven Kilometers | Distance driven |
| Engine Type | Petrol / Diesel / CNG / Electric |
| Transmission | Manual / Automatic |
| Registration Number Type | Registration details |
| Location | City |
| Status | Vehicle availability |

---

# ⚙️ Tech Stack

- Python
- Selenium
- BeautifulSoup
- Pandas
- NumPy
- Regular Expressions
- ChromeDriver
- WebDriver Manager

---

# 📂 Project Workflow

```
Cars24 Website
        │
        ▼
 Selenium Browser Automation
        │
        ▼
 Dynamic Page Rendering
        │
        ▼
 HTML Source Collection
        │
        ▼
 BeautifulSoup Parsing
        │
        ▼
 Data Extraction
        │
        ▼
 Data Cleaning
        │
        ▼
 Pandas DataFrame
        │
        ▼
 CSV Dataset
```

---

# 📁 Project Structure

```text
Cars24-Web-Scraping/
│
├── cars24_main.ipynb
├── html_files/
│   ├── delhi.html
│   ├── bangalore.html
│   ├── hyderabad.html
│   ├── chennai.html
│   ├── ahmedabad.html
│   ├── gurgaon.html
│   ├── mumbai.html
│   └── pune.html
│
├── Dataset/
│   └── cars24_dataset.csv
│
├── requirements.txt
└── README.md
```

---

# 🔍 Workflow

### Step 1

Render Cars24 webpages using Selenium.

### Step 2

Wait until all dynamic vehicle cards are loaded.

### Step 3

Save webpage HTML for each city.

### Step 4

Parse HTML using BeautifulSoup.

### Step 5

Extract vehicle information.

### Step 6

Clean missing and inconsistent values.

### Step 7

Merge all city datasets.

### Step 8

Export the final dataset into CSV format.

---

# 📦 Python Libraries

```python
beautifulsoup4
selenium
webdriver-manager
pandas
numpy
matplotlib
seaborn
```

Install using:

```bash
pip install -r requirements.txt
```

---

# 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/BHARGAVPRAVEEN-CHINTAPALLI/Cars42-EDA-Web-Scrapping.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook cars24_main.ipynb
```

---

# 📈 Applications

- Used Car Price Analysis
- Market Research
- Data Analytics
- Machine Learning
- Vehicle Price Prediction
- Exploratory Data Analysis
- Dashboard Development

---

# 💡 Future Improvements

- Automated pagination
- Scheduled scraping
- Parallel scraping
- Database integration
- API development
- Power BI dashboard
- Machine Learning price prediction

---

# 🛠 Skills Demonstrated

- Web Scraping
- Browser Automation
- Data Cleaning
- Data Extraction
- BeautifulSoup
- Selenium
- Python Programming
- Pandas
- Data Processing
- Data Collection Pipeline

---

# 👨‍💻 Author

**Bhargav Praveen**

Data Analyst | Data Science Enthusiast | Python Developer

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
