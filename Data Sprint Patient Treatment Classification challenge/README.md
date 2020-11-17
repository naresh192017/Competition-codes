<div align='left'><font size="5" color="#00000"><left><h1 style="text-transform: uppercase; text-shadow: 1px 1px;"> Data Sprint #14: Patient Treatment Classification </font></div> </h1></left>

## Help doctors predict the patient status (incare or an outcare)

<center><img src="https://dphi-courses.s3.ap-south-1.amazonaws.com/Datathons/patient_classification.jpg" width=800 ></center> 

## Objective
Build a machine learning model to predict if the patient should be classified as in care or out care based on the patient's laboratory test result.

| __Variable__ | __Definition__ |
|-------------|------------|
| HAEMATOCRIT | Patient laboratory test result of haematocrit |
| HAEMOGLOBINS | Patient laboratory test result of haemoglobins |
| ERYTHROCYTE | Patient laboratory test result of erythrocyte |
| LEUCOCYTE | Patient laboratory test result of leucocyte |
| THROMBOCYTE | Patient laboratory test result of thrombocyte |
| MCH | Patient laboratory test result of MCH |
| MCHC | Patient laboratory test result of MCHC |
| MCV | Patient laboratory test result of MCV |
| AGE | Patient age |
| SEX | Patient gender |
| SOURCE |  {1,0}The class target 1.= in care patient, 0 = out care patient |

## Evaluation Criteria
Submissions are evaluated using f1 score.

## Approach :
1. EDA
2. Building Baseline models ( Logistic Regression, Random Forest and LGBM ) 
3. Ensembling (voting and blending)

## Leaderboard Ranking : 10th rank

Link to the leaderboard [here](https://dphi.tech/practice/challenge/43#leaderboard#datathon-leaderboard).
