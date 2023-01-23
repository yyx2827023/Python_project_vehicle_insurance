# Python_project_vehicle_insurance
This is a project for vehicle insurance

Ensemble Learning-based analysis on vehicle insurance    
Author：Yixin Yang , Zhanxu Liu
May.2022-Aug.2022     
1. Calculated Pearson correlation coefficient by seaborn to capture linear correlation among variables, and performed LASSO by sklearn for feature selection
2. Generated synthetic samples of the minority class using Synthetic Minority Oversampling Technique from imbalanced-learn package to process imbalanced data
3. Checked Gaussian distribution of the insurance annual cost, and built linear regression to explore relationship between demographic variables and insurance annual cost by statsmodels.formula.api package
4. Employed ensemble learning methods including RandomForest and AdaBoost from sklearn.ensemble package, identified the top important features of buying vehicle Insurance, and plotted ROC curve to check model fit accuracy
