# Walmart-Sales-Forecasting-Using-EDA-and-Machine-Learning
![image](https://github.com/user-attachments/assets/269b7515-4bcd-4aa2-a766-d24c7942b09e)
## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Models Built](#models-built)
- [Metrics Used](#metrics-used)
- [Technologies Used](#technologies-used)
- [Observations from Machine Learning Models](#observations-from-machine-learning-models)
- [Key Insights](key-insights)
- [Recommendations](#Recommendations)
## Project Overview
This project uses a dataset of over 5,50,068 Walmart retail records to analyze customer purchase behavior and build predictive models. The objective is to forecast purchase amounts based on customer demographics and transactional features using machine learning.
## Objective
* Perform comprehensive exploratory data analysis (EDA) on Walmart's customer data
* Visualize purchase trends by demographic segments
* Evaluate model performance and extract insights from feature importance
## Dataset Overview
The dataset includes:
**550,068 rows, 10 columns**

**Key features:**
* User_ID, Product_ID, Gender, Age, Occupation
* City_Category, Stay_In_Current_City_Years, Marital_Status
* Product_Category, Purchase (target)
## Models Built
* Decision Tree Regressor
* Random Forest Regressor
## Metrics Used
* MAE( Mean Absolute Error) 
* RMSE( Root Mean Squared Error) 
* R² Score
## Technologies Used
* **Python:** Pandas, NumPy
* **Data Vizualizations:** Matplotlib, Seaborn
* **Machine Learning:** scikit-learn
## Observations from Machine Learning Models
| Model          |       MAE       |    RMSE       |   R2 Score |
|----------------|-----------------|---------------|------------|
| Decision Tree  |    2186.092937  |  2992.926859  |   0.643495 |
| Random Forest  |   2172.287559   |  2957.531020  |   0.651877 |

* Random Forest outperforms Decision Tree on all metrics (MAE, RMSE, R²).
* MAE and RMSE are slightly lower in Random Forest, indicating more accurate predictions.
* R² Score is higher (0.6519 vs. 0.6435), meaning Random Forest explains more variance in the target.
* Overall, **Random Forest** is **better** and more reliable model in this comparison.
  ## Key Insights
* City C has the highest median purchase values.
* Age group 51–55 shows the most variation in spending.
* Gender has minimal effect on purchase amounts.
* Marital status does not significantly influence spending.
  ## Recommendations
* Focus marketing on City C, which shows higher average spending.
* Target Age 51–55 with personalized offers due to their variable spending behavior.
* Promote low-performing product categories to improve visibility and sales.
  
  
