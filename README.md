# 🚴 Delivery Performance Analysis (Deliveroo)

*A case study based on food delivery platforms such as Deliveroo.*
---

This project analyses delivery performance data to identify the key factors driving late deliveries and provide insights to improve operational efficiency..

---

## 🎯 Business Problem

Late deliveries can negatively affect customer satisfaction and overall operational performance.  
The goal of this project is to analyse delivery data to identify the main causes of delays and highlight areas for improvement.

---

## 🛠️ Solution

A data-driven approach was used to analyse delivery patterns and build predictive models to identify deliveries likely to be delayed.

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

- Logistic Regression: Baseline model used for comparison  
- Random Forest: Delivered improved predictive performance  
- XGBoost: Achieved the strongest overall performance

---

## 💼 Business Impact

The insights from this analysis can help improve delivery efficiency by identifying key delay factors.  
These findings can support better route planning, resource allocation, and overall service improvement.

## 📊 Visual Insights  

### 🚚 Average Delivery Time  
![Average Delivery Time](./Average-Delivery-Time.png)  

The average delivery time is around 37 minutes, suggesting moderate efficiency but room for improvement.
---

### 📍 Delivery Distance vs Time  
![Delivery Distance and Time](./Delivery-Distance-and-Time.png)  

There is a clear relationship between delivery distance and time, with longer distances generally resulting in longer delivery times.
---

### 🛵 Delivery Method  
![Delivery Method](./Delivery-method.png)  

Different delivery methods show noticeable differences in performance. Some methods consistently achieve faster delivery times, while others are more prone to delays. This suggests that how deliveries are assigned can directly impact efficiency and overall service quality.
---

### 🚦 Traffic Condition  
![Traffic Condition](./Traffic-condition.png)  

Deliveries made under high-traffic conditions tend to take significantly longer than in low-traffic scenarios.
---

## 🔍 Conclusion & Key Findings

The analysis shows that delivery performance is largely influenced by distance, traffic conditions, and operational factors.  
Deliveries over longer distances or during high-traffic periods were more likely to be delayed.

The machine learning models, particularly Random Forest and XGBoost, outperformed Logistic Regression, indicating their ability to capture more complex patterns in the data.

Overall, the project highlights how data can be used to better understand delivery challenges and support more informed decision-making.

---

## 💡 Business Recommendations

- Optimise delivery routes based on distance and traffic patterns  
- Increase rider availability during peak demand periods  
- Use predictive models to identify deliveries at risk of delay  
- Continuously monitor delivery performance to identify new trends
   
---

## ⚠️ Limitations

- The dataset does not include external factors such as weather conditions  
- The data may not fully reflect real-time operational changes  
- Model performance may vary when applied to different datasets
  
---

## 🚀 Future Improvements

- Include additional variables such as weather and real-time traffic data  
- Test the models on larger and more diverse datasets  
- Explore more advanced modelling techniques  
- Develop a real-time monitoring system for delivery performance

---
This project demonstrates my ability to combine data analysis, machine learning, and visualisation to solve real-world business problems.
