# 📚 Web Scraping + EDA + Machine Learning Project (Books Travel Dataset)

---

## 📌 Project Overview

This project performs **Web Scraping, Exploratory Data Analysis (EDA), and Machine Learning** using Python.  

Book data (Title, Category, and Price) is scraped from an online website, cleaned, visualized, and analyzed using a Linear Regression model.

---

## 🌐 Data Source

Website scraped:  
https://books.toscrape.com/catalogue/category/books/travel_2/index.html  

---

## 🛠️ Technologies & Libraries Used

- Python  
- Requests (Web Scraping)  
- BeautifulSoup (HTML Parsing)  
- Pandas (Data Cleaning & Analysis)  
- Matplotlib & Seaborn (Visualization)  
- Scikit-learn (Machine Learning)  

---

## 📂 Project Structure

```
WebScraping-EDA-ML/
│── books_travel_dataset.csv   # Scraped dataset (Title, Category, Price)
│── web_scraping_eda_ml.py     # Web Scraping + EDA + ML code
│── README.md                  # Project Documentation
```

---

## 🔄 Project Workflow

---

### 1️⃣ Web Scraping

- Used `requests` to fetch webpage content  
- Used `BeautifulSoup` to parse HTML  
- Extracted:
  - Book Titles  
  - Category (Travel)  
  - Prices (£)  
- Saved the data into CSV file: `books_travel_dataset.csv`  

---

### 2️⃣ Data Cleaning & Preprocessing

- Loaded dataset using Pandas  
- Converted Price column to numeric format  
- Removed missing values using `dropna()`  
- Checked dataset info and structure  

---

### 3️⃣ Exploratory Data Analysis (EDA)

- Price Distribution Histogram  
- Category Distribution Count Plot  
- Data inspection using statistical methods  

---

### 4️⃣ Data Visualization

- Histogram for price distribution  
- Count plot for category analysis  
- Visualization using Matplotlib and Seaborn  

---

### 5️⃣ Machine Learning Model

- Model Used: Linear Regression  
- Train-Test Split: 80% Training, 20% Testing  
- Evaluation Metrics:
  - RMSE (Root Mean Squared Error)  
  - R² Score  

> Note: This project demonstrates the complete ML workflow on the scraped dataset.

---

## 📊 Dataset Description

| Column Name | Description                     |
|-------------|---------------------------------|
| Title       | Name of the book                |
| Category    | Book category (Travel)          |
| Price       | Price of the book in pounds (£) |

**Sample Data:**

- It's Only the Himalayas — 45.17  
- Under the Tuscan Sun — 37.33  
- A Summer In Europe — 44.34  

---

## ▶️ How to Run the Project

### Step 1: Install Required Libraries

```
pip install requests beautifulsoup4 pandas matplotlib seaborn scikit-learn
```

### Step 2: Run the Python Script

```
python web_scraping_eda_ml.py
```

### Step 3: Output

- Scraped dataset saved as: `books_travel_dataset.csv`  
- Graphs for EDA will be displayed  
- Model performance (RMSE & R² Score) will be printed in the console  

---

## 📈 Results

- Successfully scraped real-time book data  
- Cleaned and structured the dataset  
- Visualized price distribution  
- Implemented Linear Regression model for analysis  

---

## 🚀 Future Improvements

- Scrape multiple book categories  
- Add advanced ML models (Random Forest, Decision Tree)  
- Feature engineering for better predictions  
- Deploy using Streamlit for interactive dashboard  

---

## 👩‍💻 Author

**Devireddy Nikitha**  
CSE Student  

GitHub: https://github.com/nikitha-devireddy  
LinkedIn: https://www.linkedin.com/in/devireddy-nikitha  

---
