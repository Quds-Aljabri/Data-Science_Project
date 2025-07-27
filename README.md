"# Data-Science_Project" 

# 🏡 Real Estate Data Science Project – Oman Property Market

## 📌 Project Objective

This project simulates a real-world data science workflow. The goal is to collect, clean, and integrate property listings data from two real estate websites in Oman, engineer useful features, and frame a predictive modeling problem to estimate property prices.

The final output is a GitHub repository containing all project artifacts, from raw data to predictive models.

---

## 🌐 Assigned Websites

The project involves scraping data from the following real estate platforms:

- [Dubizzle Oman – Properties](https://www.dubizzle.com.om/en/properties/)
- [Hilal Properties Oman](https://hilalprp.com.om)

Each site includes listings for **properties for sale** and **for rent**.

---

## 📋 Project Workflow

### 1. 🔍 Web Scraping
- Scrape relevant property data:
  - Property title
  - Location
  - Number of rooms
  - Price (OMR)
  - Size/Area
  - Listing type (For Sale / For Rent)
- Handle pagination and dynamic content where applicable.
- Save raw data in structured CSV files for each website.

### 2. 🧹 Data Cleaning & Integration
- Clean data using Python:
  - Handle missing values
  - Standardize formats
  - Remove duplicates
- Merge datasets from both websites into one clean, consolidated CSV.
- Ensure consistent column names and data types.

### 3. 🏗️ Feature Engineering
- Generate features such as:
  - `property_title`
  - `number_of_rooms`
  - `Price_OMR`
  - `Area`
  - `For_Sale`, `For_Rent` (as binary flags)
  - `price_per_sqm`
- Apply feature scaling using:
  - `MinMaxScaler`
  - `StandardScaler`

### 4. 🤖 Predictive Modeling
- **Modeling Objective:** Predict property prices (Price_OMR).
- Dataset preparation:
  - Split features and target variable
  - Encode categorical variables
- Suggested models (using Scikit-learn):
  - Linear Regression





