## 🚴 Delivery Performance Analysis

This project explores delivery performance to understand what drives delays and how operations can be improved using data.

---

## 🎯 Business Problem

Late deliveries can negatively affect customer satisfaction and overall operational performance.  
The goal of this project is to analyse delivery data to identify the main causes of delays and highlight areas for improvement.

---

## 🛠️ Solution

A data-driven approach was used to analyse delivery patterns and build predictive models capable of identifying deliveries that are likely to be delayed.

---

## 📊 Key Insights

- Delivery distance and traffic conditions were key contributors to delays  
- Longer delivery times were often linked to high traffic levels and operational inefficiencies  
- Certain patterns in delivery behaviour highlighted opportunities for process improvement  

---

## 🛠️ Tools & Technologies

- Python (data analysis and modelling)  
- Excel (data cleaning and preparation)  
- Power BI (data visualisation)  
- Machine Learning (Logistic Regression, Random Forest, XGBoost)  

---

## ⚙️ Methodology

- Data collection from delivery-related datasets  
- Data cleaning and preparation using Excel and Python  
- Exploratory data analysis (EDA) to identify trends and patterns  
- Model development using classification algorithms  
- Model evaluation using F1-score and ROC-AUC  

---

## 📈 Model Performance

- Logistic Regression: XX% accuracy  
- Random Forest: XX% accuracy  
- XGBoost: XX% accuracy  

---

## 💼 Business Impact

The insights from this analysis can help improve delivery efficiency by identifying key delay factors.  
These findings can support better route planning, resource allocation, and overall service improvement.

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
