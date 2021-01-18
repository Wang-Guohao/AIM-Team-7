# AIM-Team-7
## Roswell Park's DBBR Cancer Patient Survival Prediction :A model that uses a dataset of various cancer cases to predict patient survival.
Team Members: Guohao Wang , Xin Jiang , Lunshu Sun and Jue Gao .
Link to AIM Datathon: https://www.kaggle.com/c/aimdatathon2020/leaderboard <br>
Link to Google Collab Notebook: https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing
### Contents

* [Problem](#Problem)
* [Solution](#Solution) (Clinical Revelance of the Model)
* [ML Pipeline](#ML-Pipeline)
* [Data Management](#Data-Management)
* [Study Design](#Study-Design)
* Exploratory Analysis (add if applicable)
* [Validation Strategies (Train and Test Data Pre-processing, Training/Validation Split)](#Validation-Strategies)
* Feature Engineering (add if applicable)
* [Model Training,Tuning (Logistic Regression, XGBoost, AUC performance metric)](#Model-Training_and_Tuning)
* [Results,Model Performance,Interpretability](#Results_Model-Performance_and_Interpretability)
* [Conclusion](#Conclusion)
* [Solution Video](#Solution-Video)
  * Link a short video (unlisted Youtube link) that walks through your approach from github and code from google collab.
* [Acknowledgments](#acknowledgments)

#### Problem
- Physcians are overwhlemed with patient cancer data, and would benefit from a system that outlined indiviaulized patients risk factors based  patient's background like gender, date of birth, enthicity aswell as familial history, primiary site, cancer stage and grading to augment their clinical decision making. 

#### Solution
- A clinical decision system to help physicians keep track of their patients' progress using their background and individualized molecular level data.

#### ML-Pipeline
- ML WorkFlow depicting the solution below.![Image](https://github.com/Wang-Guohao/AIM-Team-7/blob/main/pipline.png)
- Refer to this [sample notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for further details.
#### Data-Management
Refer to Data Pre-Processing subtitle in the [Google Collab notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for more detail. 
- Data Pre-processing/Transformations(Changing column names, Merging different data sources, etc). 
1) Merge all of data set and split into Train and Test.
2) Change column names to lowercase. 
#### Study-Design
Refer to Race, Age, Cancer Type Primary Site in the [Google Collab notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for more detail. 
-   Identify clinical goal (Prediction of cancer patient survival.)
-   Define prediction outcome (Predict cancer patient survival for quality review and better clinical decision making.)
-   Participant inclusion/exclusion criteria 

![Image](https://github.com/Wang-Guohao/AIM-Team-7/blob/main/Race_Bar_Chart.png)
This race bar plot shows that:
(2000 patients with various cancer types were included. A diverse patient population race was involved including whites (1860 [93%]),  African Americans (88 [4.5%]), American Indians (12 [0.6%]), Asians (7 [0.35%]),  Alaskan Natives (12 [1%]), Native Hawaiians (2 [0.15%]), and from other races (7 [0.45%]).

![Image](https://github.com/Wang-Guohao/AIM-Team-7/blob/main/Age_Distribution.png)
This plot is the age distribution of the patients.
The median age (interquartile range) was 62 (54-70) years old.  

36% of the patients had a paternal history with cancer and the greatest proportion was 10% prostate cancer. 39% of the patients had a maternal history with cancer and the greatest proportion was 11% breast cancer. 

![Image](https://github.com/Wang-Guohao/AIM-Team-7/blob/main/Cancer_Type_Piechart.png)
Here is the top 15 Cancer Type pie chart.
Out of 785 males,the majority of the tumors were from the prostate gland as the primary site (371[47.2%]),adenocarcinoma(496 [63%]), grade III: Poorly differentiated , dedifferentiated (369 [47%]), and stage 1 (478[60%]) . 
Out of 1215 females, the majority of the tumors were from the breast upper outer quadrant primary site(300 [24.69%]), infiltrating duct carcinoma(535 [44%]), grade II: moderately differentiated, intermediate differentiated (522 [43%]), and stage 1 (737 [60%]).

#### Validation-Strategies 
Refer to Train and Test Data Pre-processing, Training/Validation Split subtitles in the [Google Collab notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for more detail. 

-Train and Test Data Pre-processing
1) Encoding Categorical COlums. 
2) Fill NaNs. 
3) Drop columns.

-Training/Validation Split
80 % - 20 %  Split was used.

#### Model-Training_and_Tuning
Refer to Logistic Regression and XGBoost subtitles in the [Google Collab notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for more detail. 
Hyperparameters
Tuning

#### Results_Model-Performance_and_Interpretability
Refer to Results,.... subtitles in the [Google Collab notebook](https://colab.research.google.com/drive/1mzJ-p35W4LMargBNMVecX7q2fw0hsyB7?usp=sharing) for more detail. 

-Include Summary of Results/Discussion and Picture of Results here.


-Logistic Regression

![Image](https://github.com/Wang-Guohao/AIM-Team-7/blob/main/Logistic_Regression_plot.png)


#### Conclusion

Logistic Regression accuracy on test dataset was 63.75%.

#### Solution-Video

Waiting for updating.


#### Acknowledgments

