# data-science-pipeline

Code examples for data science pipeline.
See basic syntax for markdown [here](https://www.markdownguide.org/basic-syntax/).

### Remember:
- **DON'T** compute anything from the test set (the best way of thinking about the test set is that it simply doesn't exist, at least until you have already trained your model)
- **INSTEAD** build a transformation pipeline that can handle all the necessary preprocessing steps (imputing missing data, standardizing, feature engineering, dimensionality reduction) using the training set, and then apply it to test set.

### Data science pipeline:
1. Data ingestion
2. EDA
3. Data preprocessing & feature engineering
4. Model building
5. Hyperparameter tuning