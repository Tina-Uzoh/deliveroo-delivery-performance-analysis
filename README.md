🚴 Delivery Performance Analysis 

A data-driven analysis of delivery performance to identify key factors influencing late deliveries and improve operational efficiency.

🎯 Business Problem

Late deliveries negatively impact customer satisfaction and operational performance. This project explores the delivery data to understand the root causes of delays and identify opportunities for improvement.

🚀 Solution

Developed a data-driven approach using analytics and machine learning techniques to evaluate delivery performance and predict late deliveries

📊 Key Insights

Identified key variables contributing to late deliveries
Analysed delivery time patterns and operational inefficiencies
Highlighted opportunities to improve delivery performance

🛠️ Tools & Technologies
Python (Data Analysis & Modelling)
Excel (Data Cleaning & Preparation)
Power BI (Visualisation)
Machine Learning (Logistic Regression, Random Forest, XGBoost)

⚙️ Methodology
Data Collection
Data Cleaning & Preparation
Exploratory Data Analysis (EDA)
Model Development
Model Evaluation (F1-score, ROC-AUC)

## Model Performance  
- Logistic Regression: XX% accuracy  
- Random Forest: XX% accuracy  
- XGBoost: XX% accuracy 
💼 Business Impact

This project demonstrates how predictive analytics can improve delivery efficiency, reduce delays, and enhance customer satisfaction.


## 📊 Visual Insights  

### 🚚 Average Delivery Time  
![Average Delivery Time](./Average-Delivery-Time.png)  
Average delivery time varies significantly, indicating inconsistencies in operational efficiency across orders.

---

### 📍 Delivery Distance vs Time  
![Delivery Distance and Time](./Delivery-Distance-and-Time.png)  
Delivery time increases with distance, but variability suggests other factors, such as traffic and delivery conditions, also play a role.

---

### 🛵 Delivery Method  
![Delivery Method](./Delivery-method.png)  
Different delivery methods show varying performance levels, highlighting opportunities to optimise logistics strategy.

---

### 🚦 Traffic Condition  
![Traffic Condition](./Traffic-condition.png)  
Traffic congestion significantly impacts delivery delays, making route optimisation critical for performance improvement.

## 🔍 Conclusion & Key Findings

The analysis made it clear that delivery performance is strongly affected by factors such as distance and traffic conditions. Orders that travelled longer distances or were delivered during heavy traffic were more likely to be delayed.

There were also signs that operational factors, such as how deliveries are assigned, may contribute to inconsistencies in delivery time.

Among the models tested, Random Forest and XGBoost outperformed Logistic Regression, suggesting that more complex models are better at capturing patterns in the data.

Overall, the results show that delivery performance can be improved by focusing on key operational and environmental factors.

## 💡 Business Recommendations
- Adjust delivery routes based on distance and traffic conditions to reduce delays
- Plan for higher rider availability during peak periods
- Use predictive insights to flag deliveries that are likely to be late
- Continuously monitor performance data to identify new patterns over time

## ⚠️ Limitations
- The dataset does not include some real-world factors, such as weather conditions
- The data may not fully reflect real-time operational changes
- Model results may vary when applied to larger or more complex datasets

## 🚀 Future Improvements
- Include additional variables such as weather and real-time traffic data
- Test the model on larger and more diverse datasets
- Explore more advanced modelling techniques to improve prediction accuracy
- Consider building a real-time system for monitoring delivery performance
