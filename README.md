# How to Solve the Problem of Imbalanced Datasets: Meet Djinn by Tonic

Tonic's latest offering is a data synthesizer tailored specifically for data scientist's needs.  

## Meet Tonic Data Science Mode

Using powerful AI generative models, Tonic Data Science Mode (DSM) takes a dataset from an application database - such as PostgreSQL or Oracle - a data warehouse - such as BigQuery or Snowflake - or simply from a CSV file, and creates rows of synthetic data that align with the trends in your data to allow you to build models with greater predictive power.

In this [blog post](link to blog) we use a dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) to explore how data from DSM helps improve classification model performance when working with imbalanced datasets. We compare the performance of Logistic Regression, XGBoost, and CatBoost models trained on datasets augmented using DSM, SMOTE and SMOTE-NC.

Through addressing the biases associated with training models on imbalanced data by rebalancing the imbalanced class, we find that DSM-augmented data outperforms the other augmentation methods for the CatBoost and XGBoost models. 

<hr>

## How to follow along

Head to [Tonic](https://app.tonic.ai/onboarding/create-account) to create your free account. Once you're logged in perform the following steps to get faking!
1. Create a workspace <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/DVuaf1aPnR4skLht2l/giphy.gif">
</p>
<br>
2. Configure your source data (in this example we upload a CSV) <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/cZbjDUabeeGG2OnDjR/giphy.gif">
</p>
<br>
3. Create a model with a SQL query - making sure to specify appropriate datatypes and column names <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/EGJYgk7AiiB2IEa9dG/giphy.gif">
</p>
<br>
4. Set your model parameters and run your model <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/fJHqnEKcVoJjWwcnHC/giphy.gif">
</p>
<br>
5. Check your synthesis report and copy your python snippet into your jupyter notebook<br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/I7KeiCq57xAmWsOf3Y/giphy.gif">
</p>
<br>

Recreate this experiment for yourself - head to [Tonic](https://app.tonic.ai/onboarding/create-account) to create your account and start your free trial!
