# **Oil Well Profitability Prediction**  
**Supervised Machine Learning for Investment Decisions**  

## **Overview**  
This project applies **regression modeling** to predict oil well profitability in three regions. Using **machine learning algorithms**, the goal is to identify the most **profitable region for investment** while minimizing financial risks.  

## **Business Problem**  
A company is evaluating potential oil field investments and needs to determine which region will yield the **highest profit with minimal risk**. Given historical **geological data and oil reserves**, we use predictive modeling to:  
- Estimate oil well productivity (**target variable: barrels of oil per well**).  
- Select the most profitable region based on statistical analysis and uncertainty measures.  
- Minimize financial risks by incorporating confidence intervals and loss functions.  

## Data
The dataset consists of three CSV files containing geographical and oil well drilling data:

- `geo_data_0.csv` - Oil well data from region 0.
- `geo_data_1.csv` - Oil well data from region 1.
- `geo_data_2.csv` - Oil well data from region 2.

Each dataset includes:
- **Well ID**: Unique identifier for each oil well.
- **Coordinates**: Geographical location of the well.
- **Predicted Reserves**: Estimated amount of oil in barrels.

These datasets are stored in the `data/` folder for easy access.


**Key features:**  
- `f0`, `f1`, `f2` → Geological indicators.  
- `product` → Target variable (barrels of oil per well).  

## **Methods & Techniques**  
- **Exploratory Data Analysis (EDA)** → Identified data distributions, outliers, and correlations.  
- **Machine Learning Models** → Trained **Linear Regression** to predict oil well output.  
- **Region Selection Strategy** → Compared predicted oil yields across regions.  
- **Risk Analysis & Bootstrapping** → Calculated confidence intervals and **quantified investment risks**.  

## **Key Results**  
- **Model Performance**: Evaluated RMSE and mean predicted profit per region.  
- **Best Region Selection**: Identified the **most profitable oil field** with the highest expected return.  
- **Risk Assessment**: Simulated **loss probabilities** to ensure strategic investment decisions.  

## **Conclusions & Business Impact**  
- **Data-driven investment strategy**: Using machine learning, the company can maximize returns and mitigate financial risks.  
- **Statistical risk assessment**: Bootstrapping and loss function analysis helped **identify safer investments**.  
- **Actionable insights**: The model provides a **data-backed approach** to selecting oil wells **before drilling**.  

## **Next Steps & Improvements**  
- Explore **non-linear models** (Random Forest, Gradient Boosting) for better prediction accuracy.  
- Improve **feature selection** by incorporating additional **geological indicators**.  
- Consider external factors (**oil prices, economic conditions**) for better risk forecasting.
  
## Connect & Explore More
* Email: rhiannon.filli@gmail.com
* LinkedIn: linkedin.com/in/rhiannonfilli
