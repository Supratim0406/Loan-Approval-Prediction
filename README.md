# Loan-Approval-Prediction

A loan is a bank's main source of revenue. The profits earned through loans account for most of the bank's profits. Even though the bank accepts the loan following a lengthy verification and testimony process, there is no guarantee that the chosen candidate is the right one. When done manually, this operation takes a long time. We can predict whether a given hopeful is safe or not, and the entire testimonial process is automated using machine literacy. Loan Prognostic is beneficial to both bank retainers and hopefuls.

The Bank wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out online application forms. These details are Gender, Marital Status, Education, number of Dependents, Income, Loan Amount, Credit History, and others.

To automate this process, they have provided a dataset to identify the customer segments that are eligible for loan amounts so that they can specifically target these customers.

As mentioned above this is a Binary Classification problem in which we need to predict our Target label which is “Loan Status”.

Loan status can have two values: Yes or No.

Yes: if the loan is approved No: if the loan is not approved So using the training dataset we will train our model and try to predict our target column that is “Loan Status” on the test dataset.

Banks consider numerous factors when determining an applicant's loan eligibility. Machine learning models can assist in this process, offering a common application in finance. 
<img width="2710" height="1806" alt="image" src="https://github.com/user-attachments/assets/7ae39193-12df-471d-bd8c-cadfe583ac25" />


I developed a loan approval prediction model following these steps:

1. Data Preparation

* Collected historical loan data (approved and denied)
* Cleaned and preprocessed data:
* Handled missing values
* Encoded categorical variables
* Scaled/normalized numerical features

2. Exploratory Data Analysis (EDA)

* Analyzed dataset structure (rows, columns, data types)
* Examined target variable distribution (loan approval status)
* Visualized data using bar plots, pie charts
* Explored feature distributions using histograms, box plots
* Identified outliers

3. Data Splitting
   
 * Divided data into training and testing sets

4. Model Selection

* Chose algorithms suitable for binary classification:
* Logistic Regression
* Random Forests
* Support Vector Machines
* XGBoost

5. Model Training

* Trained selected models on the training dataset
* Model Evaluation

6. Assessed performance using metrics:
* Accuracy
* Precision
* Recall
* F1-score
* Hyperparameter Tuning
* Optimized model parameters using Grid Search

7. Results

* Achieved 86% accuracy with logistic regression
* Noted potential for improvement through:
  1. Feature engineering
  2. Exploring alternative algorithms
     
This approach provides a structured method for predicting loan approvals, aiding banks in their decision-making process while considering various applicant characteristics.
