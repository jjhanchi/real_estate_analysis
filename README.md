# real_estate_analysis
Analysis of Real Estate data to explore house price prediction models

* The original dataset used comes from Kaggle and a usability rating of 10: https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset
* For purposes of reproducibility I have included a copy of the source dataset is in this repository as [ **realtor-data.rar** ]
* Trough visual analysis using Tableau Public it became evident most of the records (~90%) were located in the US North East
* Surprisingly, this dataset had lots of duplicate entries ( ~80% )
* To keep the analysis within bounds all zip codes outside the ranges 0xxxx and 1xxxx were eliminated
* Additionally, entries with null values in key fields were also removed
* Once the above was completed the techniques of K-means clustering and Linear Regression were applied using Python
* The Linear Regression models had at best R2 scores of 0.4 - 0.5
* In Tableau, a quick quadratic polynomial regression yielded models with R2 scores of 0.6 (a slight improvement)
* You can find details of the Tableau story at https://public.tableau.com/app/profile/jose.hanchi/viz/Real_Estate_Analysis_16989027751240/RealEstate
