# Problem Definition 
Anti-Cancer Drug Activity Prediction. The goal of this problem is to predict the activity of anti-cancer drugs against different cancer cell lines. The problem dataset contains over 12,000 features and 10,000 drug-cell line combinations. 

# Problem Statment
**These is a classification problem** to develop a predictive model that can accurately predict the anti-cancer activity of a set of drug compounds, based on their molecular structures.. The performance of the model will be evaluated using various metrics, including accuracy, precision, recall, and F1 score. </br>


**The input** is a dataset of drug compounds represented by their molecular structures. The dataset consists of around 4,000 drug compounds and their corresponding activity levels, measured using a bioassay..</br>
**The output** the label represent if the chemical compound is positive against non-small cell lung cancer, or negative:
* 1 for possitive
* 0 for negative.</br>

**The goal** is to develop a predictive model that can take in the molecular graph representations of the drug compounds and predict their activity levels against cancer cells. 

**The challenges** 
1. Data sparsity and imbalance: The dataset of drug compounds and their activity levels may be sparse, meaning that there is a limited amount of data available for training and testing the predictive model. Additionally, the dataset may be imbalanced, meaning that there are significantly more compounds of one activity level than the other. This can make it difficult to train a predictive model that is both accurate and generalizes well to new data.

2. Complex molecular structures: Drug compounds can have complex molecular structures that require specialized methods for feature extraction and representation. The molecular structures may also contain noise or errors, which can affect the performance of the predictive model.


