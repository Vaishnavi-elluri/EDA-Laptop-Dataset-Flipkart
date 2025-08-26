# EDA-Laptop-Dataset-Flipkart
## 📌 Overview

This project focuses on scraping laptop product data from Flipkart using BeautifulSoup and performing Exploratory Data Analysis (EDA) to uncover meaningful insights. The end goal is to understand product trends, pricing, and customer preferences in the laptop market.

## 🎯 Problem Statement

Flipkart hosts thousands of laptops with varied specifications. Manually analyzing them is inefficient.
➡️ Objective: Build an automated pipeline to scrape data, clean it, and analyze it for insights.

### 📥 Data Collection

✅ Used requests to send HTTP requests to Flipkart.

✅ Used BeautifulSoup to parse HTML content.

✅ Scraped laptop details including:

#### Brand Name 🏷️

#### Model Name 💻

#### Processor Details ⚡

#### Price 💰

#### Storage & RAM 💾

#### Ratings & Reviews ⭐

#### Screen Size 📐

#### Operating System 🖥️

📊 Total Data Collected: 912 rows & 13 columns
🔄 After cleaning: 492 unique rows

## 🧹 Data Cleaning

Removed 420 duplicate rows

Handled null values in critical columns

Converted datatypes (e.g., ratings, screen size → numeric)

Exported final dataset to CSV

## 🔍 Exploratory Data Analysis (EDA)

Key insights derived:

📈 Price vs RAM/Storage → Higher specs generally increase price.

⭐ Ratings distribution → Most laptops fall in the mid-to-high rating range.

🏷️ Brand comparison → Identified top-performing brands in terms of pricing & reviews.

## ⚙️ Tech Stack

#### Python 🐍

#### Libraries: requests, BeautifulSoup, pandas, matplotlib, seaborn

#### Jupyter Notebook for development

## 🚀 How to Run

1. Clone the repo

2. Install dependencies:

3. pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook


Run all cells to scrape, clean, and analyze data



## 📊 Outcomes / Key Insights

Identified which laptop brands dominate Flipkart listings.

Found price ranges where most laptops are concentrated.

Analyzed how ratings and reviews impact laptop popularity.

Observed storage (SSD/HDD) and RAM distribution across laptops.

Discovered trends in operating systems and screen sizes.

## 📬 Contact / Connect with Me
- Author: Vaishnavi Elluri  
- LinkedIn: https://www.linkedin.com/in/vaishnavi-elluri-721293289/ 
- Email: ellurivaishnavi55@gmail.com
