<h1>Telecom Churn, Kaggle Competition and Cousera-Advanced-Datascience-Capstone-Project</h1>

<h2>Motivation:</h2>
<p>I had to find project for the Coursera Advanced Data Science Capstone.</p>

<h2>Project Description:</h2>
<p>In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.</p>

<h3>Project Structure:</h3>
<p>The structure of this project is divided into two  different jupyter notebook:</p>
<ol>  
  <li><b>Telecom_data_prep.ipynb</b>
    <p>In this notebook, a thorough exploration of the data is made as well as data cleaning, filling with missing values and saving the cleaned data into a new dataset to be used in the next notebook.</p>
  </li>
    
  <li><b>Analysis_data_cleaned.ipynb</b>
    <p>In this notebook, cleaned data is loaded. </p>
    <p>Features and Target are separated.</p>
    <p>Three "scenarios" considered:</p>
    <ul>
      <li>Imbalanced Data</li>
      <li>Balanced Data - <b>SMOTE</b></li>
      <li>Balanced Data - <b>SMOTE</b> and <b>RandomUnderSampling</b></li>
    </ul>
  </li>
</ol>

<p>These <b>three</b> scenarios were fed into two different models, <b>Decision Tree Classifier</b> and <b>Random Forest Classifier</b> with the standard hyper-parameters to establish a baseline.</p>
<p>The next step, after evaluating which model performed better in which scenario, the best combination was selected for further analysis or improvements. </p>
<p>A GridSearchCV for the best combination of hyperparameters was performed for the RandomForest and <b>SMOTE</b> and <b>UnderSampling</b></p>
<p>A SMOTE strategy evaluation was also performed to check if we could still improve the overall performance of the model.</p>

<p>To finish the analysis a Keras Deep Learning network was also defined and tested.</p>



