# Tanzania_waterpoint_classification

## Business Problem:
Tanzania is a developing country, it has a very large population of over 57,000,000. The country struggles to provide clean water.
There are many water points already established in the country, but some are and some are completely non-functional

## Scope:
To create a model that helps predicting, the waterpoints that are functional and non functional.
This would, help the Government know the areas it should be  focusing more on, in order to provide proper cleaning water to its population

## Data:
The data was acquired from https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/ <br/>
Rows = 59400 , Columns = 40

## Files:
The repository has the following files:<br/>
Data : It contains the main data that the cleaning was done on<br/>
Data Cleaning :  This notebook, consists of the data cleaning process.<br/>
EDA: This notebook involves Exploratory Data Analysis on the cleaned data</>
Base_Model: This notebook, consists of the code that deals with evaluating the model performances on the train and test sets.

## Project Details:
Data Modelling:</br>
- All the data was processed by OneHotEncoding and then standardised through sklearn pipeline </br>
- GridsearchCV was further cross validation</br>
- The classification models used in this project are:</br>
  - Logistic Regression
  - Knn Classifier
  - RandomForest Classifier
  - XGBoost Classifier 
- The best performing model was RandomForest Classifier, with a accuracy score of 92%</br>
<img width="643" alt="Screen Shot 2022-10-06 at 2 15 05 PM" src="https://user-images.githubusercontent.com/110783008/211254252-3a726b5a-ce2a-4b91-99ec-2c9d0ba97b8d.png">
- Model metrics:</br>
<img width="592" alt="Screen Shot 2022-10-06 at 3 48 49 PM" src="https://user-images.githubusercontent.com/110783008/211255125-7f6bcb2d-5d90-4e0c-998d-e81cd1961b96.png">
- Feature Engineering:</br>
<img width="715" alt="Screen Shot 2022-10-07 at 3 08 18 AM" src="https://user-images.githubusercontent.com/110783008/211255247-6a4c91e2-d020-42ac-a962-bcd9a5180813.png">

<img width="379" alt="Screen Shot 2022-10-07 at 3 09 05 AM" src="https://user-images.githubusercontent.com/110783008/211254623-3a54fc4b-8b58-4dc6-8883-114f05817a8c.png">

## Summary:
-58% of all waterpoints in Tanzania are functional.<br/>
-The model is 92% accurate.<br/>
-The Government of Tanzania can use features like quantity of water, extraction type of waterpoints,  the height ,payments being made etc, to make further  repairs on water points that are non functional<br/>
-This model can be further used by the Government to analyze the future improvements.



