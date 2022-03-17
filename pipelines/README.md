# Pipelines

See below for descriptions of components

## Components

### 1 Acquire Data

Web download can be used. 

Examples of web data:

* Primary tumor features (CSV): https://www.openml.org/data/get_csv/3594/dataset_113_primary-tumor.arff


Usage:

```
Args:
        url: A string containing path to the url for file download.     
```

### 2 Data Processing

Data processing of downloaded object.

There are several components of data processing:

* Feature Construction
	- Imputation
	- Scaling
	- Other transformations

* Cohort Construction


### 3 Feature Selection

Examples: ANOVA, Chi-Square


### 4 Classification

Examples: XGBoost, Logistic Regression, ANN, CNN


