<br clear="both">

<h1 align="left">Individual Project 3 - Telcom Customer Churn Prediction</h1>

###

<h2 align="left">Introduction</h2>

###

<br clear="both">

<p align="left">This project focuses on building a machine learning model to classify and predict Telcom Customer Churn</p>

###

<h2 align="left">Objective</h2>

###

<p align="left">1. To identify the relationship of the features and the target class (Churn)<br><br>2. To handle the imbalanced dataset<br><br>3. To build a suitable model to predict customer Churn</p>

###

<h2 align="left">Dataset</h2>

###

<p align="left">This dataset is selected from Kaggle, named the Telcom Customer Churn Dataset. This dataset included 7043 data points and 21 features</p>

###

<h4 align="left">Dataset Features</h4>

###

<p align="left">CustomerID: Unique identifier<br><br>Gender: Male/Female<br><br>SeniorCitizen: 0 = No, 1 = Yes<br><br>Partner: Yes/No<br><br>Dependents: Yes/No<br><br>Tenure: Number of months with the company<br><br>PhoneService: Yes/No<br><br>MultipleLines: Yes/No/No phone service<br><br>InternetService: DSL/Fiber optic/No<br><br>OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Yes/No/No internet service<br><br>Contract: Month-to-month/One year/Two year<br><br>PaperlessBilling: Yes/No<br><br>PaymentMethod: Electronic check/Mailed check/Bank transfer/Credit card<br><br>MonthlyCharges: Amount billed monthly<br><br>TotalCharges: Lifetime total charges<br><br>Churn: Yes/No</p>

###

<h2 align="left">Tool, Skills, Model Used</h2>

###

<h4 align="left">Tool & Library Used</h4>

###

<p align="left">1. Python <br>2. Pandas<br>3. NumPy<br>4. Scikit-learn<br>5. Matplotlib<br>6. Seaborn</p>

###

<h4 align="left">Skill Used</h4>

###

<p align="left">1. Data Preprocessing<br>2. EDA (Exploratory Data Analysis)<br>3. Model Training - Machine Learning<br>4. Model Evaluation</p>

###

<h4 align="left">Model Used</h4>

###

<p align="left">1. Decision Tree<br>2. Random Forest<br>3. K-Nearest Neighbors (KNN)</p>

###

<h2 align="left">Project Workflow</h2>

###

<p align="left">1. Data collection<br>Dataset “Telcom Customer Churn.csv” is collected from Kaggle that uploaded by BlastChar in 2018<br><br>2. EDA<br>This phase is used to better visualize and understand the current data and to determine which data preprocessing and data model should be applied in this project.<br><br>3. Data Preprocessing<br>Data preprocessing includes data cleaning, transformation, and normalization to handle missing and imbalanced data, making the data suitable for analysis. <br><br>4. Split Train Data and Test Data<br>We will divide the dataset into two parts. One part is the training set, and the other part is the testing set. The training set is used to build and train the machine learning model. The test set is used to evaluate how well the model performs on the data.<br><br>5. ML Model<br>Now that we have the data, we must train machine learning algorithms with KNN, Decision Trees, and Random Forests to identify which customers are likely to leave the Telco Customer service.<br><br>6. Model Evaluation<br>After we train the model, we need to see how well it works. We will use evaluation metrics such as accuracy, precision, recall, and F1-score to measure this. These numbers tell us if the model is good at predicting Telco Customer Churn. <br><br>7. Predict<br>Finally, we use the model we trained and tested to make predictions about customers, including those we know little about. This helps the Telco Customer business identify customers who're likely to leave and take steps to keep them as Telco Customers.</p>

###

<h2 align="left">Result</h2>

###

<p align="left">1. Customers with certain contract types and payment methods are more likely to churn<br><br>2. Class imbalance significantly affects model performance<br><br>3. Ensemble models (Random Forest) perform better for this dataset<br>(Cross Validation accuracy: 84%, Model evaluation accuracy: 77.86%)</p>

###

<h2 align="left">Future Improvement</h2>

###

<p align="left">1. Include other classification models (Naive Bayes, XGBoost)<br><br>2. Develop a web app or desktop app(GUI) for users to predict the result themselves.</p>

###
