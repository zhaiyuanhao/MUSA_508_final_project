# MUSA_508_final_project
In this program, we will develop software to predict the gentrification of city areas.

# Documents Explanation
In this repository, there are two documents for the final project:
Gentrification_Prediction_Model_Report_Yuanhao_Jiewen.pdf[https://github.com/zhaiyuanhao/MUSA_508_final_project/blob/main/Gentrification_Prediction_Model_Report_Yuanhao_Jiewen.pdf]
This report is for the director of Smart Cities, you can find the research process of our model, including an explanation of the methodology, results of the model testing, and recommendations for implementation.

technical documents from R markdown [https://github.com/zhaiyuanhao/MUSA_508_final_project/blob/main/MUSA508_final_Yuanhao_Jiewen.html]
This file is the model developing process, including the data collecting process, index calculating process, model building, model testing, and validation process.

# Study Areas
We will train the prediction model by using the data from the Chicago Data Portal.
And test the model on the Philadelphia.

# Data Collecting 
**1 socioeconomic factor changes**:
median income changes,
education level composition changes,
age's composition changes,
families' types changes,
marriage status,
tenure status,
median housing price,
ethnicity composition

**2 Housing status**:
building types,
building year,
condition

**3 local amenity factors**:
Coffee shop numbers,
Number of restaurants, grocery stores, parks nearby,
education facilities numbers nearby,

*Data Source*: Longitudinal Tract Database[https://s4.ad.brown.edu/Projects/Diversity/Researcher/Bridging.htm]

# Model Selecting
We use a logistic regression model, The predicted result will be 0 or 1.
A detailed explanation will be provided in the report[https://github.com/zhaiyuanhao/MUSA_508_final_project/blob/main/Gentrification_Prediction_Model_Report_Yuanhao_Jiewen.pdf].

# Reference
https://urbanspatialanalysis.com/portfolio/predicting-gentrification-using-longitudinal-census-data/
