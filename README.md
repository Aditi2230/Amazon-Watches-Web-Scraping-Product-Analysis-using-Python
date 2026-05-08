# ⌚ Amazon Watches Web Scraping & Product Analysis using Python

## 📌 Project Overview

This project focuses on scraping Amazon watch product data using Python and performing data cleaning, transformation, and exploratory data analysis (EDA) to uncover insights about popular brands, customer reviews, pricing trends, and product ratings.

The project demonstrates practical usage of:

* Web Scraping
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Python Automation

---

# 🚀 Technologies Used

* Python
* BeautifulSoup
* Requests
* Pandas
* Matplotlib

---

# 📂 Dataset Information

The dataset was scraped directly from Amazon India watch listings across multiple pages.

### Extracted Features:

* Brand
* Product Description
* Star Ratings
* Number of Reviews
* Price
* Delivery Date

---

# ⚙️ Project Workflow

## 1️⃣ Web Scraping

Used Python libraries such as `requests` and `BeautifulSoup` to scrape watch product information from multiple Amazon pages.

### Key Tasks:

* Sent HTTP requests with browser headers
* Parsed HTML content
* Extracted product details
* Scraped multiple pages dynamically

---

## 2️⃣ Data Cleaning

Performed extensive data preprocessing using Pandas.

### Cleaning Steps:

* Removed commas and symbols from numeric columns
* Converted ratings, prices, and reviews into numeric format
* Handled missing values
* Removed duplicate products

---

## 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to identify trends and customer behavior.

### Insights Generated:

* Top 5 most reviewed products
* Top 5 brands by total reviews
* Price distribution of watches
* Relationship between ratings and prices
* Brand-wise popularity trends

---

# 📊 Visualizations

The project includes multiple charts such as:

* Bar Charts
* Histograms
* Scatter Plots

### Sample Analyses:

✔️ Top Reviewed Products
✔️ Most Popular Watch Brands
✔️ Price Distribution
✔️ Price vs Rating Analysis

---

# 📈 Key Learnings

Through this project, I learned:

* Real-world web scraping techniques
* HTML parsing with BeautifulSoup
* Handling unstructured web data
* Data cleaning and preprocessing
* Exploratory Data Analysis using Python
* Data visualization techniques

---

# 📁 Project Structure

```bash
Amazon-Watches-Web-Scraping/
│
├── amazon_watches_scraping.ipynb
├── amazon_watches_cleaned.csv
├── README.md
└── charts/
```

---

# ▶️ How to Run

## Clone Repository

```bash
git clone <your-repository-link>
```

## Install Required Libraries

```bash
pip install pandas matplotlib requests beautifulsoup4
```

## Run Notebook

Open Jupyter Notebook and run:

```bash
amazon_watches_scraping.ipynb
```

---

# 📌 Future Improvements

* Add Selenium for dynamic content scraping
* Build an interactive dashboard
* Automate daily scraping
* Perform sentiment analysis on reviews

---

# ⭐ Conclusion

This project successfully demonstrates how Python can be used to scrape, clean, analyze, and visualize real-world e-commerce data to derive valuable business insights.

---
