# CTR-prediction
This study focuses on improving Click-Through Rate (CTR) prediction in online advertising and content recommendation systems. Accurate CTR prediction is vital for optimizing marketing efforts and enhancing user experiences. The Kaggle competition dataset is used for this purpose and prediction model is developed by using Catboost Algorithm. 

CatBoost is a supervised machine learning technique employed within the Train Using AutoML tool. It relies on decision trees for tasks involving classification and regression. The name CatBoost signifies its primary attributes: the ability to handle categorical data (represented by "Cat") and its utilization of gradient boosting (signified by "Boost").

CatBoost is a good choice, but the best model depends on your specific dataset and experiments. It's always a good idea to compare CatBoost's performance with other models like LightGBM, XGBoost, and Factorization Machines to find the optimal model for your task. 

Other one of the main purpose of this study is using the Weight&Bias platform and see gow we can read the model development results from W&B platform in an efficient way.

# Dataset
The dataset used in this study is obtained from the Kaggle competition in the [link][id/name]. It includes 11 days click data.
The dataset includes 3 different files; train, test, and submission. In this study, only random 10000 data points in the training dataset will be used to make quick analysis and model development. Subsampling will be done without considering class balance.

[id/name]: https://www.kaggle.com/competitions/avazu-ctr-prediction/overview


# Environment
To install the dependencies to run the notebook, you can use Anaconda. Once you have installed Anaconda, run:

`$ conda env create -f environment.yml`

# Notebook 
[CTR-EDA-feature-engineering.ipynb][notebook1] notebook includes feature engineering steps for the dataset. 
[model_development.ipynb][notebook2] includes all model development and hyperparameter tuning processes by using the Weight&Bias platform.

[notebook1]: https://github.com/ftmoztl/CTR-prediction/blob/main/CTR-EDA-feature-engineering.ipynb
[notebook2]: https://github.com/ftmoztl/CTR-prediction/blob/main/model-development.ipynb

# Proposed Resources
 

# Contribution
If you want to contribute please, send your pull request. All contributions are welcome!

#
Please check that repository for updates, for opening issues or sending pull requests.