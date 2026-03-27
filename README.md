# 🏨 Hotel Booking Analysis & Cancellation Prediction

_End-to-end Data Analysis project using Python to analyze hotel booking behavior, cancellation patterns, seasonal demand, and pricing trends._

---
# 📌 Table of Contents

- <a href="#overview">Overview</a>

- <a href="#business-problem">Business Problem</a>

- <a href="#dataset">Dataset</a>

- <a href="#tools--technologies">Tools & Technologies</a>

- <a href="#project-structure">Project Structure</a>

- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>

- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>

- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>

- <a href="#predictive-modeling">Predictive Modeling</a>

- <a href="#how-to-run-this-project">How to Run This Project</a>

- <a href="#final-recommendations">Final Recommendations</a>

- <a href="#author--contact">Author & Contact</a>
---

## 📌 Overview
This project performs an in-depth analysis of hotel booking data to understand **customer behavior, pricing sensitivity, and cancellation patterns**.

The focus is on identifying:
- Why customers cancel bookings  
- Which factors influence cancellations  
- How hotels can optimize pricing and strategy  

The project bridges the gap between **data analysis and real-world business decision-making**.

---

# 🎯 Business Problem

- Hotel businesses frequently struggle with:

- High cancellation rates

- Seasonal demand fluctuations

- Revenue instability

- Over-dependence on Online Travel Agencies (OTAs)

- This analysis helps answer:

- Which hotel type faces higher cancellations?

- Does lead time impact cancellation probability?

- How does pricing influence booking behavior?

- Which market segment dominates revenue?

---

## 📂 Dataset
The dataset contains booking-level information for both **City Hotels** and **Resort Hotels**.

### Key Features:
- `hotel` → Type of hotel (City / Resort)  
- `lead_time` → Days between booking and arrival  
- `arrival_date_month` → Month of arrival  
- `adr` → Average Daily Rate (price per night)  
- `country` → Customer origin  
- `market_segment` → Booking channel  
- `is_canceled` → Target variable  

📁 File: `hotel_bookings 2.csv`

---

## 🛠️ Tools & Technologies
- **Python** → Core programming  
- **Pandas & NumPy** → Data manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis  
- **GitHub** → Version control  

---

## 🗂️ Project Structure

    Hotel_Analytics_Project/
    │
    ├── Data Analysis (Hotel Booking).ipynb
    ├── hotel_bookings 2.csv
    ├── Report.pdf
    ├── README.md
    └── .ipynb_checkpoints/

---

## 🧹 Data Cleaning & Preparation

Data preprocessing steps included:

- Handling missing values in columns like `children`, `country`, etc.  
- Removing duplicates and inconsistent records  
- Converting date-related columns into proper formats  
- Encoding categorical variables where necessary  
- Removing outliers in pricing (`adr`)  
- Feature understanding and validation  

### Outcome:
A clean and structured dataset ready for reliable analysis.

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analysis Performed:
- Cancellation vs Non-cancellation distribution  
- Monthly booking trends  
- Price (ADR) vs cancellation relationship  
- Hotel type comparison (City vs Resort)  
- Country-wise analysis  
- Booking channel distribution  

---
## ❓ Research Questions

1. What factors influence booking cancellations?  
2. How can cancellations be reduced?  
3. How can pricing strategies be improved?  

---

## 🔍 Key Findings

- Around **37% bookings are canceled**  
- **Higher prices lead to higher cancellations**  
- City hotels receive more bookings than resort hotels  
- Resort hotels have relatively higher cancellation rates  
- **August** has the highest bookings  
- **January** has the highest cancellations  
- **Portugal** has the highest number of cancellations  
- **46% bookings come from Online Travel Agencies (OTA)**  
- Only ~4% bookings are direct  

---

## 🤖 Predictive Modeling

### Target Variable:
`is_canceled`

### Models that can be used:
- Logistic Regression  
- Decision Tree  
- Random Forest  

### Goal:
Predict booking cancellations and take preventive actions.

---

## ▶️ How to Run This Project

### Step 1: Clone the repository
git clone https://github.com/your-username/Hotel_Analytics_Project.git

### Step 2: Navigate to folder
cd Hotel_Analytics_Project

### Step 3: Install dependencies
pip install pandas numpy matplotlib seaborn

### Step 4: Run notebook
jupyter notebook

---

## 💡 Final Recommendations

### 1. Dynamic Pricing
Adjust prices based on:
- Demand  
- Season  
- Customer segment  

### 2. Reduce Price Sensitivity
- Offer non-refundable discounted plans  
- Provide early booking benefits  

### 3. Seasonal Strategy
- Run campaigns in January to reduce cancellations  

### 4. Increase Direct Bookings
- Website discounts  
- Loyalty programs  

### 5. Reduce OTA Dependency
- Improve direct marketing channels  

### 6. Improve Resort Hotel Strategy
- Weekend packages  
- Holiday discounts  

---

## 📈 Business Impact

If implemented, these strategies can:
- Reduce cancellation rate  
- Increase occupancy  
- Improve revenue predictability  
- Enhance customer retention  

---

## 🧠 Key Learnings
- Importance of pricing in customer decisions  
- Data-driven decision making  
- Translating analysis into business insights  
- Understanding customer behavior  

---

## 👨‍💻 Author

**Aniket Shah**  
GitHub: https://github.com/Aniketshah1234  
Email: your-email@example.com  

---









