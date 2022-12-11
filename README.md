<h2 align="center"> About the project </h2>

<p align = "justify">
In this project I've used a number of combinantions of different resampling techniques with various predictive classifiers to see which combination is working best in detecting whether a transaction is a valid transaction or a fraud. As mentioned above, the features are scaled and the names of the features are hidden due to privacy reasons.

</p>

---


<h2 align='center'> About the Dataset </h2>

<p align = "justify">
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset contains transactions that occurred in two days, where we have 492 fraud transactions out of 284,807 total transactions. The dataset is highly imbalanced, the positive class (frauds) accounts for 0.172% of all transactions.
</p>

<p align = "justify">
The dataset contains only numerical input variable columns which are the result of a PCA transformation done on the original dataset. Due to confidentiality issues, Original features were not provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of a fraud tansaction and 0 otherwise. 
</p>

---

 <h2 align = "center" >Outline</h2>
<p>
<h3>I. Exploratory Data Analysis</h3>
<ol type = None>
<li>a) Analysis of the data</li>
<li>b) Barplot</li>
<li>c) Distplot</li>
</ol>

<h3>II. Data Preprocessing</h3>
<ol type = None>
<li>a) Scaling using Robust Scaler</li>
<li>b) Splitting the Data into test and train sets<li>
</ol>
<h3>III. Resampling and Classification</h3>
<ol type = None>
<li>a) Resampling
    <ol type = None>
      <li>1) SMOTE (Synthetic Minority Oversampling Technique)
      <li>2) Random Over Sampling
      <li>3) Random Under Sampling
      <li>4) NearMiss
    </ol>
<li>b) Classification
    <ol type = None>
      <li>1) Logistic Regression
      <li>2) K-Nearst Neighbors
      <li>3) Decision Tree
      <li>4) Random Forest
    </ol>
</ol>

<h3>IV. Result</h3>
<ol type = None>
<li>a) Evaluation Metrics
<li>b) Confusion
</ol>

</p>
