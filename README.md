🦠 COVID-19 Vaccination Data Analysis & Predictive Modeling
📌 Project Overview

This project focuses on analyzing global COVID-19 vaccination data to understand vaccination trends across countries and to predict fully vaccinated population rates using machine learning techniques. The objective is to transform real-world public health data into meaningful insights that support data-driven decision-making.

🎯 Objectives

Analyze global vaccination coverage and trends across countries

Identify key factors influencing full vaccination rates

Build a predictive machine learning model for vaccination outcomes

Visualize insights for better interpretability and understanding

📊 Dataset

Source: Our World in Data (OWID)

Data Type: Real-world global COVID-19 vaccination data

Key Features Used:

total_vaccinations_per_hundred

people_fully_vaccinated_per_hundred

daily_vaccinations_per_million

location

date

The dataset contains vaccination statistics from multiple countries and is continuously updated by OWID.

🛠️ Tools & Technologies

Programming Language: Python

Libraries Used:

Pandas, NumPy – Data processing

Matplotlib, Seaborn, Plotly – Data visualization

Scikit-learn – Machine learning

Joblib – Model persistence

🔍 Methodology
1. Data Collection

Loaded vaccination data directly from the OWID public GitHub repository.

2. Data Cleaning & Preprocessing

Removed missing and invalid records

Filtered country-level data using ISO codes

Aggregated vaccination metrics by country and date

Converted date fields into appropriate formats

3. Exploratory Data Analysis (EDA)

Analyzed the distribution of fully vaccinated populations

Visualized relationships between total vaccinations and full vaccination rates

Compared vaccination trends across countries

4. Feature Engineering

Selected relevant numerical features influencing vaccination outcomes

Applied standard scaling to normalize input features

5. Model Development

Built a Random Forest Regressor to predict:

people_fully_vaccinated_per_hundred

Split data into training and testing sets

Evaluated model performance using appropriate metrics

6. Model Interpretation

Analyzed feature importance to identify key drivers of vaccination success

📈 Key Insights

Countries with higher total vaccinations per hundred tend to have significantly higher fully vaccinated rates.

Daily vaccination rate is a critical factor influencing full vaccination coverage.

Machine learning models can effectively capture non-linear relationships in public health data.

📁 Project Structure
├── Covid Analysis.ipynb
├── Covid Vaccine Analysis.docx
├── vaccination_model.pkl
├── scaler.pkl
├── README.md

🚀 Future Enhancements

Implement time-series forecasting for vaccination trends

Include region-specific or income-level analysis

Compare multiple machine learning models for performance optimization

Deploy the model using a web interface or dashboard

📌 Conclusion

This project demonstrates the application of data analytics and machine learning on real-world public health data. It highlights the ability to clean, analyze, model, and interpret large datasets while deriving actionable insights—skills essential for data-driven roles in consulting and analytics.

👤 Author

Yash Dhudat
Final Year B.E. Information Technology (2026)
