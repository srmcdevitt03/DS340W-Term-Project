# DS340W-Term-Project

### Stephen McDevitt & Jacob Lukasik

## Research Paper 1

**Paper Link:** [Demystifying Fraudulent Transactions and Illicit Nodes in the Bitcoin Network for Financial Forensics](https://dl.acm.org/doi/pdf/10.1145/3580305.3599803)

[**GitHub Repository Link**](https://github.com/git-disl/EllipticPlusPlus?tab=readme-ov-file)

[**Input Data Link**](https://drive.google.com/drive/folders/1MRPXz79Lu_JGLlJ21MDfML44dKN9R08l)

## Research Paper 2 - Parent Paper

**Paper Link:** [Pump and Dumps in the Bitcoin Era: Real Time Detection of Cryptocurrency Market Manipulations](https://massimolamorgia.com/assets/pdf/Pump_Dump__ICCCN__2020.pdf)

[**GitHub Repository and Input Data Link**](https://github.com/SystemsLab-Sapienza/pump-and-dump-dataset/tree/master)

## Research Paper 3

**Paper Link:** [To the moon: defining and detecting cryptocurrency pump-and-dumps](https://crimesciencejournal.biomedcentral.com/articles/10.1186/s40163-018-0093-5)

[**GitHub Repository Link**](https://osf.io/827wd/files/osfstorage)

[**Input Data Link**](https://osf.io/654ay)

# Our Work

Our project seeks to detect anomalies in cryptocurrency transactions, building upon ideas from the above three research papers. In our modified implementation, we take a look further than just a Random Forest model. We sought out to see how Random Forest, AdaBoost, Gradient Boosting Machines, and XGBoost effectively detect anomalies in transactions. From here, we selected our two best models, Random Forest and AdaBoost, to create an ensemble learning method to detect anomalies. Lastly, we began using a different idea all together with an Isolation Forest model, a model specifically made to detect anomalous data points.

## Running Our Code:

Prior to running our code, make sure you have the following libraries installed in your Python environment:

  - pandas

  - matplotlib

  - seaborn

  - scikit-learn

  - xgboost

You can install all of them by running the following in your python terminal:
`pip install pandas matplotlib seaborn scikit-learn xgboost`
