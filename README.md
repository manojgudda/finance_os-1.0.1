# FinanceOS 🚀
**An Advanced Personal Finance & Analytics Dashboard**

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Django](https://img.shields.io/badge/Django-DarkGreen.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-Green.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-Purple.svg)

FinanceOS is a premium, comprehensive SaaS-style financial tracking application. Built as a flagship portfolio project, it moves far beyond simple CRUD operations. It integrates real-time REST APIs, AI vision processing, algorithmic debt splitting, and web scraping into a highly responsive, modern dark-mode interface.

---

## ✨ Core Features

* **📊 Dynamic Analytics Dashboard:** Live summary cards, visual budget progress bars, and an animated Chart.js spending breakdown that reacts to your data in real-time.
* **🤖 AI Vision Scanner (OCR):** Upload a restaurant receipt and let the Optical Character Recognition (powered by Tesseract) automatically extract the merchant title and total amount to log the transaction.
* **📈 Live Crypto Trading Desk:** Fetches real-time cryptocurrency data via the CoinGecko REST API. Users can "trade" virtual assets and track their live portfolio value dynamically.
* **🍕 Splitwise Algorithm:** A shared-expense engine that divides bills among friends, tracks outstanding debts, and automatically logs your personal share directly to the master ledger.
* **🛒 Product Intelligence Tracker:** Simulates web-scraping for e-commerce URLs to track product prices, calculates buy recommendations based on historical highs/lows, and compares competitor pricing.
* **🏛️ Tax Hub & Smart Tools:** Instant calculators for GST and New Regime Income Tax Returns (ITR), plus a "Smart Cart" affordability engine.
* **🏆 Gamified Financial Health Score:** An algorithm that analyzes your spending against the 50/30/20 rule to generate a dynamic "Credit Score" style rating of your financial habits.

---

## 🛠️ Tech Stack

* **Backend Engine:** Python, Django
* **Database:** MongoDB (via `pymongo`)
* **Frontend UI:** HTML5, CSS3, JavaScript, Bootstrap 5.3
* **Data Visualization:** Chart.js
* **AI & Machine Learning:** `pytesseract` (Tesseract OCR), `Pillow`
* **Web Scraping & APIs:** `requests`, `BeautifulSoup4`

---

## 🚀 Getting Started

Since the project code is provided as a `.zip` archive in this repository, follow these steps to run it locally on your machine.

### Prerequisites
Make sure you have **Python**, **MongoDB** (running locally or via Atlas), and **Tesseract-OCR** installed on your system.

### Installation

1. **Download and Extract:**
   Download the latest `finance_os.zip` file from this repository and extract it to your desired folder.

2. **Open your terminal and navigate to the folder:**
   ```bash
   cd path/to/extracted/finance_os
3. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   
   # on Windows
   venv\Scripts\activate

   # On Mac/Linux:
   source venv/bin/activate
   
4.**Install the required dependencies:**
  ```bash
    pip install django pymongo requests beautifulsoup4 pytesseract Pillow
```
5.**Run the application:**
  ```bash
  python manage.py runserver
```
***
GitHub: @manojgudda !
