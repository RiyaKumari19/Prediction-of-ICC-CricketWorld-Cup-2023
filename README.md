# Prediction-of-ICC-CricketWorld-Cup-2023

Predicting the Finalist Teams and Winner of the ICC Cricket World Cup 2023_**<br/>

_DATASET DESCRIPTION_<br/>
**1. ICC CWC 23 Points Table (Scrapped)**<br/>
_Dataset Link_ : Web_Scrapping_DM_Challenge.ipynb<br/>
_Description_: The dataset was collected through web scraping from Cricbuzz, a prominent sports platform. It contains cricket performance details for various countries, including the number of matches played, matches won and lost, points earned, and net run rate. The use of web scraping allows for a comprehensive and up-to-date overview of cricket statistics, providing valuable insights into the performances of different teams in specific matches.<br/>
**Note**: Attributes description in provided in the respective ipynb file.<br/>
_Purpose_: Comprehensive overview of cricket performances by different nations.<br/>

**2. ODI Men's Cricket Match Data (2002-2023)**<br/>
_Dataset Link_ : https://www.kaggle.com/datasets/utkarshtomar736/odi-mens-cricket-match-data-2002-2023<br/>
_Description_ : This dataset provides comprehensive information about ODI cricket matches, making it suitable for analysis and research in the field of cricket statistics and performance evaluation.<br/>
**Note**: Attributes description in provided in the respective ipynb file<br/>

**ML pipeline.**<br/>

-> Extracting semifinalist teams from scrapped points table<br/>
-> Feature selection using correlation analysis<br/>
-> Splitting of data<br/>
-> Scaling of data<br/>
-> Model Training on historic data<br/>
               → Logistic Regression  
               → Decision tree Classifier  
               → Random Forest Classifier  
               → ANN  
-> Model Evaluation and Testing<br/>
-> Prediction for finalist<br/> 
-> Prediction For Winner<br/>

We have used two approaches:<br/> 
**1)Considering the problem statement as Multiclass Classification task** <br/>
_**File : Final_ICC_WC23_predictions.ipynb**_<br/>
Prediction :<br/> 
-->**Finalists**:<br/>

<img width="265" alt="2" src="https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/75682006/e56479a6-5195-4ecd-8603-60e97424b212">

Choosing _ANN Model_<br/> 
Predicted finalists:<br/> 
**_India and Australia_**<br/>

Based on the finalists<br/> 
_**Winner :**_<br/>

<img width="249" alt="image" src="https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/137144018/3eca8e39-6c7e-45d4-9ead-77340fa04db9">

_**AUSTRALIA :(**_


**2)Considering the problem statement as Regression task.**<br/>
_**File: Final_Regression_TaskDM_3.ipynb**_ <br/>
Predictions :<br/> 
![4](https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/75682006/ff0669e2-0532-4027-b0ac-444354dcd1ef)
![5](https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/75682006/f38f9dc5-dc01-454f-8ba4-bc539804cb9a)

**Task 2.2: Predicting the finalist teams/Playing 11.**<br/>
**_File: Prediction_of_Playing_11_DATA_MINING_.ipynb**<br/>
DATASET DESCRIPTION<br/>
_Batting Dataset Link:_ : https://drive.google.com/file/d/1v6YTvUfGlPnohr0DtIcBQ2vQmAAtt-jY/view?usp=sharing
_Bowling Dataset Link:_ https://drive.google.com/file/d/1hs5pvLrj-vpCWEfRPSnFgK58ZOdiS1Nr/view?usp=sharing

_Description:_ <br/>
The dataset presented here was obtained through the process of web scraping from ESPNcricinfo, a prominent and reliable source for comprehensive cricket-related information. Web scraping is a technique that automates the extraction of data from web pages, allowing us to compile a detailed dataset on various aspects of cricket matches. ESPNcricinfo, being a renowned platform, provides up-to-date and in-depth statistics, including the number of matches played, matches won and lost, points earned, and net run rate for each country. Through this web scraping process, we aim to deliver accurate and timely insights into the performance of cricket-playing nations, enabling a thorough analysis of team dynamics and tournament standings.

**Prediction of playing eleven for Team India:-**

![final1](https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/75682006/ed9a6fcf-198b-4e0c-8f72-3a8ce47d379b)

**Prediction of playing eleven for Team Australia:-**

![final2](https://github.com/Chinmaya54/DM_Challenge_WC_Winner/assets/75682006/4df1ebb8-9146-4df7-b270-598f9724dde0)

