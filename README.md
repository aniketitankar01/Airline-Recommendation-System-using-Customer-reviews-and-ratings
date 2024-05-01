# Airline-Recommendation-System-using-Customer-reviews-and-ratings


### Extracting the Data:
1. Began the analysis by conducting exploratory data analysis (EDA) on all datasets.
2. Focused on the dependent variable 'Recommended' to check for class balance.
3. Discovered that the dataset was nearly balanced, which was favorable.

### Feature Engineering:
1. Made necessary changes and extracted new features to enrich the EDA process.

### Exploratory Data Analysis (EDA) of Categorical and Numerical Variables:
1. Examined both categorical and numerical variables.
2. Explored their correlation, distribution, and relationship with the dependent variable.
3. Encoded categorical variables and removed some numerical features exhibiting multicollinearity, used solely for EDA purposes.

### Data Sampling:
1. Performed data sampling due to the dataset's large size and computational expense.
2. Randomly selected 6000 records for further analysis and model training.

### Text Feature Processing:
1. Conducted necessary natural language processing (NLP) operations on the 'Customer Review' text feature.
2. Utilized TFIDF vectorization to transform text data into numerical form.
3. Addressed dimensionality issues by performing PCA (Principal Component Analysis) and selecting the top 1000 features.

### Model Training:
1. Split the prepared data into training and testing sets.
2. Explored several individual models, ranging from simple Logistic Regression to complex ensemble models like Random Forest, Extra Trees, Gradient Boosting, and XGBoost.
3. Aimed to enhance model performance through hyperparameter tuning.

## Summary:
The analysis workflow encompassed various stages, including data exploration, feature engineering, preprocessing, and model training. Techniques such as feature extraction, data sampling, and dimensionality reduction were utilized to optimize model performance while managing computational resources effectively. Thorough model evaluation and hyperparameter tuning ensured the selection of robust and effective predictive models for the Airline Recommendation System.
