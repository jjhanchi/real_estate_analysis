# real_estate_analysis
Analysis of Real Estate data to explore house price prediction models

* The original dataset used comes from Kaggle and a usability rating of 10: https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset
* For purposes of reproducibility I have included a copy of the source dataset in
* Trough visual analysis using Tableau Public it became evident most of the records were located in the US North East
* Surprisingly, this dataset had lots of duplicate entries (nearly 80%)
* To keep the analysis within bounds all zip codes outside the ranges 0xxxx and 1xxxx were eliminated
* Additionally, entries with null values in key fields were also removed
* Once the above was completed the techniques of K-means clustering and Linear Regression were applied using Python
