# CTR-prediction
This study focuses on improving Click-Through Rate (CTR) prediction in online advertising and content recommendation systems. Accurate CTR prediction is vital for optimizing marketing efforts and enhancing user experiences. The Kaggle competition dataset is used for this purpose and the prediction model is developed by using the Catboost Algorithm. 

CatBoost is a supervised machine learning technique employed within the Train Using AutoML tool. It relies on decision trees for tasks involving classification and regression. The name CatBoost signifies its primary attributes: the ability to handle categorical data (represented by "Cat") and its utilization of gradient boosting (signified by "Boost").

CatBoost is a good choice, but the best model depends on your specific dataset and experiments. It's always a good idea to compare CatBoost's performance with other models like LightGBM, XGBoost, and Factorization Machines to find the optimal model for your task. 

One of the main purposes of this study is to use the Weight&Bias platform and see how we can read the model development results from W&B platform in an efficient way.

# Dataset
The dataset used in this study is obtained from the Kaggle competition in the [link][id/name]. It includes 11 days of click data.
The dataset includes 3 different files; train, test, and submission. In this study, only random 10000 data points in the training dataset will be used for quick analysis and model development. Subsampling will be done without considering class balance.

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
Through this study, the following websites and notebooks are used. You can also get help from these resources.

* [Mobile Ads Click-Through Rate (CTR) Prediction Blog][link1]
* [Catboost Algorithm Docs][Link2]
* [Catboost Algorithm Article][Link3]
* [Kaggle Useful Notebook][Link4]
* [Github repo][Link5]

[Link1]:https://towardsdatascience.com/mobile-ads-click-through-rate-ctr-prediction-44fdac40c6ff
[Link2]:https://catboost.ai/en/docs/
[Link3]:https://arxiv.org/pdf/1810.11363.pdf
[Link4]:https://www.kaggle.com/code/pointerfly/easy-catboost
[Link5]:https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/Click-Through%20Rate%20Prediction.ipynb


# Contribution
If you want to contribute please, send your pull request. All contributions are welcome!

#
Please check that repository for updates, for opening issues or sending pull requests.