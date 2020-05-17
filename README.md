# Adult Income Prediction
A prediction model to determine if a person's income is over $50,000 a year.

## Dataset
The dataset is extracted from the 1994 Census database and is available on the [UCI repository](https://archive.ics.uci.edu/ml/datasets/adult). The size of the dataset is 48,842 rows and includes 14 attributes such as age, gender, occupation, number of hours the individual works per week, etc.

## Approach
- Exploratory data analysis (uni-variate and bi-variate)
- Data preprocessing (deduplication, handling missing values)
- Classification using logistic regression
- Classification using a gradient boosting machine
- Feature engineering

## Results
Algorithm | Accuracy | Area under the curve
--- | --- | ---
**Logistic regression** | 81.63% | 0.862
**Gradient boosting machine** | 82.58% | 0.881
