## Predicting category of interest rate
Here, goal is to use training dataset to predict the Interest rate as of 3 categories (1 / 2 / 3) that will be assigned to each loan in our test set.
```
Competition Type : Multiclass Classification

Number of Classes : 3

Evaluation metric : f1_weighted score

Private Leaderboard Rank : 84 out of 8587 particpants
```

The competition was hosted on ```https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-for-banking/```.


## Techniques Used 
- Eploratory Data Analysis and Feature Engineering 
- Model selection was done using cross valiadtion score which resulted XGBoost as the model with highest f1 weighted score.
- Data pre-processing techniques like binning and polynomial features were used.

**For detailed implementation refer JanataHack Machine Learning for Banking (A.V) notebook**

### Any suggestions or advice are welcome..!!

