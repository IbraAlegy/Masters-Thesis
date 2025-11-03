# Masters-Thesis

**Description**

This repository contains all the notebooks that were used for RUL prediction of battery B0018. There are a total of 9 notebooks.
Notebooks 1-4 are mainly for converitng raw data from NASA battery datasets into CSV. They also include descriptive statistics of each battery (B0005, B0006, B0007 and B0018).
Notebooks 5-8 are used for feature extraction per battery and the four excel files are representatives of the feature extractions and that will be used in notebook B0018 RUL Prediction.
The final notebook is where prediction of RUL is done, using Linear Regression, Random Forest and XGBoost.

The Datasets used can be retrieved from: https://phm-datasets.s3.amazonaws.com/NASA/5.+Battery+Data+Set.zip

**Contents**

1. B0005.ipynb — convert raw Battery B0005 data to CSV and save outputs.

2. B0006.ipynb — convert raw Battery B0006 data to CSV and save outputs.

3. B0007.ipynb — convert raw Battery B0007 data to CSV and save outputs.

4. B0018.ipynb — convert raw Battery B0018 data to CSV and save outputs.

5. B5 V1.ipynb — extract features from B0005 CSV and save to AV_b05.xlsx.

6. B6 V1.ipynb — extract features from B0006 CSV and save to AV_b06.xlsx.

7. B7 V1.ipynb — extract features from B0007 CSV and save to AV_b07.xlsx.

8. B18 V1.ipynb — extract features from B0018 CSV and save to AV_b018.xlsx.

B0018 RUL Prediction.ipynb — load the four .xlsx feature files, predict RUL using Linear Regression, Random Forest and XGBoost.


