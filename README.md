


# Telecom-Customer-Churn-Analysis-&-Prediction

## Project Overview

This application is designed to help businesses predict customer churn, which refers to the likelihood of customers discontinuing their services or subscriptions. By identifying customers at risk of churn, businesses can implement targeted retention strategies to improve customer satisfaction and reduce revenue loss. Utilizing the Gradient Boosting model for prediction and an analytic customer dashboard on Power BI enables proactive customer retention and profitability enhancement in the telecom sector. Additionally, interactive visualizations are deployed through Streamlit to offer stakeholders actionable insights via a user-friendly web app interface.

## Data Source
Using the Customer Churn dataset as the source of our data. "Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]. You can find the dataset here: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Technologies Used

* Power BI
* Python
* Streamlit
* Pandas
* Plotly
* Scikit-learn
* SMOTEENN
* Joblib 

## Key Features

- **Comprehensive Customer Insights:** Leverage Power BI for in-depth analysis of customer behavior, demographics, and usage patterns.
- **Transparent Churn Comparison:** visualize and compare actual churn rates with predicted churn probabilities to assess model accuracy.
- **Streamlined Prediction Process:** Utilize the Gradient Boosting model via Streamlit for seamless churn prediction, enabling quick decision-making.
- **Interpretation Assistance:** Receive clear explanations of churn predictions and influential factors, aiding in understanding and actionability.
- **Tailored Retention Strategies:** Generate actionable recommendations based on prediction results to implement targeted retention efforts and reduce churn.
- **Data Security Measures:** Ensure the safety and confidentiality of customer data with stringent security protocols in place.
- **Interactive Visualization:** Engage stakeholders with interactive charts and graphs on Power BI and Streamlit for dynamic exploration of churn trends and insights.


# Data Visualization 
## Telecom Customer Churn Dashboard Summary

 Analyze customer segmentation based on demographics, usage patterns, and contract types to gain insights into churn behavior over time, while ensuring data security measures align with regulatory compliance standards. For full experience and interaction with the dashboard, Here is the link to the dashboard
- 🎯 **Customer Segmentation:** Utilize Power BI's advanced analytics to segment customers based on various criteria such as demographics, usage behavior, and contract types, enabling targeted marketing campaigns and personalized retention strategies.
- 📈 **Churn Trend Analysis:** Employ interactive visualizations to identify trends and patterns in churn behavior over time, enabling businesses to anticipate potential churn spikes and take proactive measures to mitigate customer attrition.
- 🔒 **Data Security Measures:** Implement role-based access control, data encryption, and regular security audits to ensure the confidentiality and integrity of customer data, fostering trust and compliance with data protection regulations.
- 📊 **Performance Metrics Tracking:** Track key performance indicators (KPIs) such as churn rate, customer lifetime value (CLV), and customer acquisition cost (CAC) to evaluate the effectiveness of retention efforts and optimize resource allocation.

- ![img1](https://github.com/user-attachments/assets/9cbac213-b6b5-4b20-8cb6-c3ce51ed350e)


## Customer Profile Overview

- 👤 **Customer ID:** Unique identifier facilitating personalized engagement and loyalty programs for enhanced customer experience.
- 🔄 **Churn Index:** Dynamic metric gauging the propensity of customers to churn, enabling proactive retention measures and revenue protection.
- 💰 **Total Charge:** Financial indicator reflecting customer value and profitability, guiding pricing strategies and targeted promotions.
- 🛡️ **Risk Level:** Visualize churn risk levels to prioritize retention efforts and allocate resources effectively for maximum impact.
- 📝 **Personal Details:** Dive into demographic insights such as age, gender, and location to tailor offerings and communication channels to specific customer segments.
- 📄 **Contract Details:** Understand contract specifics like type, duration, and terms to optimize renewal strategies and minimize churn risk.
- 💼 **Additional Insights:** Explore service usage patterns, feedback, and engagement metrics to craft personalized retention strategies and foster long-term loyalty.

- ![imag2](https://github.com/user-attachments/assets/4b6ece5d-c8b9-4388-a986-f95e2ed82be9)



## Customer Churn Reasons Overview

- 💰 **Total Charge Analysis:** Understand how spending habits influence churn, aiding in pricing adjustments and retention planning.
- 💵 **Total Charge of Risk Customers:** See how much revenue is at stake from high-risk customer churn, guiding targeted retention efforts.
- 🛡️ **Risk Group Distribution:** Get a clear picture of customer risk levels to prioritize retention resources effectively.
- 📈 **Number of Risky Customers:** Know the number of customers at risk and their financial impact, aiding in resource allocation.
- 🔄 **Churn Reason Analysis:** Identify why customers churn to address underlying issues and improve retention strategies.
![imag3](https://github.com/user-attachments/assets/915d2ebc-dce9-4827-8b41-618ade4385e5)


# Model Prediction - Streamlit Web App

 Explore our Streamlit web app featuring a robust churn prediction model powered by Gradient Boosting Classifier. Predicting churn probabilities with precision, this tool empowers businesses to preemptively retain valuable customers, optimizing retention strategies for enhanced profitability and customer satisfaction. With a user-friendly interface and actionable insights, stay ahead in the competitive landscape with our data-driven solution. 


#### Prediction Options
*Choose between online prediction for individual customers or batch prediction for multiple customer records. Get real-time insights or analyze churn in bulk, with detailed explanations and recommendations provided for both modes.*


# Benefits

- **Improved Customer Retention:** By identifying customers at risk of churn, businesses can implement targeted retention strategies to reduce churn rates and increase customer loyalty.
- **Enhanced Decision Making:** The app provides valuable insights into the factors influencing churn, helping businesses make informed decisions about resource allocation and customer engagement.
- **Cost Savings:** Retaining existing customers is often more cost-effective than acquiring new ones. By reducing churn, businesses can save on acquisition costs and increase revenue.
- **Competitive Advantage:** By proactively addressing churn, businesses can differentiate themselves from competitors and build a reputation for excellent customer service.

# Challenge & Limitations

The Customer Churn Prediction App may exhibit limitations such as potential bias in model predictions, challenges in interpreting complex model decisions, and the need for continuous updates to address evolving customer behavior and market dynamics.

## How It Works

1. **Choose Prediction Mode:** Select whether you want to predict churn for individual customers online or in bulk by uploading a CSV file.
2. **Input Customer Data:** For online prediction, enter the relevant customer information such as tenure, services used, and contract details. For batch prediction, upload a CSV file containing multiple customer records.
3. **View Prediction Results:** Once the prediction is complete, the app displays the likelihood of churn for each customer along with detailed insights and recommendations.
4. **Take Action:** Based on the insights provided, businesses can take proactive steps to retain at-risk customers and improve overall customer satisfaction.
5. **Download Results:** If needed, users can download the prediction results for further analysis or reporting purposes.


## Project Structure

*   `data/`: Contains raw telecom datasets (.csv, .h5, or other format)
*   `codels/`: Gradient Boosting model  (e.g., a .pkl or .joblib file)
*   `code/`:  Script for data cleaning, feature engineering, and train/test splits.
*   `app.py`: Core Streamlit application code. 

