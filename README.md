## 📈 Project Data Case: Tiller’s Restaurant Analytics

##  Industry: Business Management
##  Difficulty: Medium

[Tiller](https://www.tillersystems.com/) by Sumup offers comprehensive solutions for restaurant management, lacking only in analytical tools.

## 🪟 Overview

This project aims to enhance Tiller's restaurant management system with analytical tools. By leveraging a dataset of restaurant orders across Paris, we seek to provide insights to restaurant owners for better decision-making and improved performance.

### 💡 Hypotheses:

| Hypothesis                                                  | User Story                                                                                                       | Specifications                                                                                               | Acceptance Criteria                                                                                                                                         |
|-------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Restaurants located in high-traffic areas generate higher total revenue compared to less frequented locations | As a restaurant owner, I need to choose better locations for new branches and analyze sales patterns based on different areas in Paris for marketing purposes, enhancing restaurant services and gaining higher revenue. | - Calculate the total revenue generated by each restaurant. <br> - Identify areas with high revenue. <br> - Display sales volumes for each item category. | - Final data can be displayed clearly in a heatmap or geographical chart. <br> - The report should clearly display the sales volumes for each item category in a format that is easy to understand. |
| Examine sales trends over time to identify peak hours, days, and months | As a restaurant owner, I want to examine sales trends over time to identify peak hours, peak days, and peak months. This will help me optimize staffing levels, inventory management, and marketing strategies to maximize revenue and customer satisfaction. | - Retrieve sales data from the "order_data" and "Payment_data" tables. <br> - Calculate the total revenue generated during each time interval. <br> - Identify peak sales periods. | - Final data can be displayed clearly and concisely in one chart. |



### 📑 Dataset File
The dataset file for this project can be found [here](dataset_schema.md)


### ⁉️ Q&A

**Question:** Do you understand your data?
**Answer:** Yes

**Question:** Do you have all the data you need?
**Answer:** No

**Question:** Do you need to look for more? 
**Answer:** NO


## 🛠️ Tech Stack

- [Looker](https://lookerstudio.google.com/s/lfVl7mkRGdQ)
- [BigQuery](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssmart-bite-final-da-project!2sTiller_Dataset)
- [Google Sheets](https://docs.google.com/spreadsheets/d/1IPDQ9qLjIOauvk-IAzmQg59IiZ3dZsMGiWmy10FII_k/edit?usp=sharing)
- [Notion](https://www.notion.so/SmartBites-Empowering-Restaurants-with-Data-driven-Insights-1ddce15ea3f44a8c9b3e65d9ec148c2e?pvs=4)



### 🧽 Data Cleaning:

#### 📱 Clean Order Data Table
- Change column names into meaningful names.
- Check the Primary key.
- Check for duplicate values.
- Check for null values.
- [Query Link](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1ssmart-bite-final-da-project!2sus-central1!3sbc86bd9e-1b26-4b18-8902-266623a3b227!2e1)

#### 👤 Clean Order Line Table
- Change column names into meaningful names.
- Check the Primary key.
- Check for duplicate values.
- Check for null values.
- [Query Link](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1ssmart-bite-final-da-project!2sus-central1!3sa6d189ec-7622-44f5-8406-52c65a99e717!2e1)

#### 💸 Clean Payment Data Table
- Change column names into meaningful names.
- Check the Primary key.
- Check for duplicate values.
- Check for null values.
- [Query Link](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1ssmart-bite-final-da-project!2sus-central1!3s6e6e02e8-378c-46b8-9a1a-f01702cb09b6!2e1)

#### 🏪 Clean Store Data Table
- Change column names into meaningful names.
- Check the Primary key.
- Check for duplicate values.
- Check for null values.
- [Query Link](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1ssmart-bite-final-da-project!2sus-central1!3s27ebf52f-ba56-4597-a89c-8d22bd774f3d!2e1)


### 👨‍👩‍👧‍👦 Join tables:

Combine all tables, incorporating relevant metrics to enhance data visualization and analysis capabilities.



### 📊 Dashboard:

<img src="https://drive.google.com/uc?id=1DSJE0VleR58mXwZBEsox_x5lVNar3QQs" width="400">
<img src="https://drive.google.com/uc?id=1XhRtl52tFI0fE-Dc8XxfSXOFw3J_2DTK" width="400">
<img src="https://drive.google.com/uc?id=1pfF1PA6R3rowHwE7u2ZcOBCvKv7kC_tO" width="400">
<img src="https://drive.google.com/uc?id=1HVeOmsINwgNdUb36VUjsC0oGaaDd7U9y" width="400">




### 🎖️ Our team:

👥 Meet the Team:

-  Fatima Alzahrani 
-  Kenaz Baharith 
-  Leenah Saeed 
-  Bashair Al Olwi






