![JanataHack-Cross-sell-prediction-thumbnail-1200x1200](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/cover_5-thumbnail-1200x1200.png)

# JanataHack-Cross-sell-prediction by AnalyticsVidhya

Link to the competition [here](https://datahack.analyticsvidhya.com/contest/janatahack-cross-sell-prediction/).

## Problem Statement:

**Building a model to predict whether a customer would be interested in Vehicle Insurance or not**

## Data Description:


| __Variable__ | __Definition__ |
|-------------|------------|
| id         | Unique ID for the customer     |
| Gender         | Gender of the customer     |
| Age         | Age of the customer     |
| Driving_License         | 0 : Customer does not have DL, 1 : Customer already has DL     |
| Region_Code        | Unique code for the region of the customer     |
| Previously_Insured        | 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance     |
| Vehicle_Age         | Age of the Vehicle     |
| Vehicle_Damage         | 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.    |
| Annual_Premium         | The amount customer needs to pay as premium in the year     |
| Policy_Sales_Channel         | Anonymised Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.     |
| Vintage        | Number of Days, Customer has been associated with the company     |
| Response        | 1 :  Customer is interested, 0 : Customer is not interested     |

## Evaluation Metric:
The evaluation metrics for this competition is [ROC AUC Score](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html).	

## Approach :
1. Feature engineering
2. Building Baseline models ( cat boost and LGBM ) 
3. Ensembling (blending)

## Leaderboard Ranking :
1. private leaderboard : 10th rank
2. public leaderboard : 37th rank 

Link to the leaderboard [here](https://datahack.analyticsvidhya.com/contest/janatahack-cross-sell-prediction/#LeaderBoard).
