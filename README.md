# NYC Airbnb Market Analysis: Pricing Strategy & Predictive Modeling

## Project Overview
This project explores the NYC Airbnb market to identify key drivers of rental pricing. By performing Exploratory Data Analysis (EDA) and building a Random Forest Regressor, I improved the model's predictive power from an initial **R² of 0.01 to 0.46**.

## Key Features
* **Univariate Analysis:** Identified right-skewed pricing and bimodal availability patterns.
* **Segment Analysis:** Compared Short-Term (<30 days) vs. Long-Term stays, finding a 7x higher review velocity in short-term listings.
* **Predictive Modeling:** Built a Random Forest model with feature engineering and outlier treatment (filtering prices > $500).

## Key Findings
1. **Operational Strategy Matters:** `availability_365` was the #1 predictor of price, outweighing specific neighborhood locations.
2. **The "Professional" Split:** The market is divided between casual hosts and "Power Hosts" managing multiple listings.
3. **Data Velocity:** Short-term rentals provide significantly more social proof (2.27 reviews/month) than long-term stays (0.32).

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook

## Visualizations
![Feature Importance]<img width="1648" height="682" alt="Screenshot 2026-01-10 142127" src="https://github.com/user-attachments/assets/2270efb6-af0f-491b-a5bd-0b77d03fe03f" />
![Price Distribution]<img width="1197" height="715" alt="Screenshot 2025-12-30 132845" src="https://github.com/user-attachments/assets/2141c74c-7eca-4afd-b20d-b00320962f86" />

