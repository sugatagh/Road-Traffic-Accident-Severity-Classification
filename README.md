# Road Traffic Accident Severity Classification

- The severity of road traffic accidents may depend on several factors, including the attributes of the involved vehicles, drivers, casualties, and surrounding conditions.

- In this project, we aim to predict the severity of an accident in terms of a given hierarchy (_slight_, _serious_, and _fatal_), with the help of information on the relevant attributes.

- A detailed [**exploratory data analysis**](https://en.wikipedia.org/wiki/Exploratory_data_analysis) on the dataset is carried out.

- The observations obtained from EDA are used in the [**data preprocessing**](https://en.wikipedia.org/wiki/Data_Preprocessing) stages.

- We employ [**decision tree**](https://en.wikipedia.org/wiki/Decision_tree), [**random forest**](https://en.wikipedia.org/wiki/Random_forest), [**XGBoost**](https://en.wikipedia.org/wiki/XGBoost), and [**ExtraTrees**](https://en.wikipedia.org/wiki/Random_forest#ExtraTrees) classifiers to predict the severity of an accident as _slight_, _serious_, or _fatal_.
- We apply [**hyperparameter tuning**](https://en.wikipedia.org/wiki/Hyperparameter_optimization) to the XGBoost classifier, which appears to perform best among the baseline candidates. We also tune the ExtraTrees classifier and the random forest classifier, as their performance is very close to that of the XGBoost classifier.
- The final model obtains a weighted [**F1-score**](https://en.wikipedia.org/wiki/F-score) of $0.795060$ on the test set.