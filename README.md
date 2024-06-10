### EDA and modeling of patient data for Women in Data Science Datathon
##### Predicting a timely diagnosis in Breast Cancer Patients - Women in Data Science Datathon

#### The project is based on a real-world Gilead Sciences' oncology dataset, consisting of Breast Cancer patient data, demographic data and air quality data
#### It includes:
1. [Data Cleaning and Missing Values Imputation using ML](https://github.com/anopsy/equity_healthcare/blob/main/ml-for-missing-values.ipynb)
2. [Experimenting with models/ code refactoring](https://github.com/anopsy/equity_healthcare/blob/main/eda_voting.ipynb) 

#### What I could improve in eda_voting.ipynb:
1. Rotate labels in the plots
2. Change n_iters from 10 to more in Hyperparams Tuning
3. Visualize the results of HyperparamsTuning
4. Compare hard voting versus soft voting using ROC_AUC curves
5. Analysis of feature importances
6. Incorporate the results from KerasTuner and compare to other estimators

#### What I did but removed from the notebook:
1. NaiveBayes - I tried GaussianNB but the results were poor so dropped it
2. KNNNeighboursClassifier _ I tried but the results were poor
3. Stacking - I got a problem with Stacking Ensemble outputting non-string column names. Lost a bit time here and decided to go for a VotingEnsemble
   
  #### F1 Initial Score Results 
![f1init_score](https://github.com/anopsy/equity_healthcare/assets/74981211/c9831632-f863-4c49-acae-cbd918f40939)

  #### F1 Tuned Score Results
![f1tuned_score](https://github.com/anopsy/equity_healthcare/assets/74981211/eb31b774-3ea4-4265-9529-05f96d88a653)

