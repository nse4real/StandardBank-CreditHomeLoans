# StandardBank-CreditHomeLoans
Standard Bank, a financial institution, is embracing the digital transformation and looking to use new technologies to provide their customers with a range of services through their mobile devices. One area that the bank is focusing on is improving the process for potential borrowers to apply for home loans. Currently, this process is done manually and can take 2-3 days to complete. In order to streamline this process and provide faster responses to borrowers, the bank plans to use machine learning to assess the credit worthiness of borrowers by implementing a model that predicts the likelihood of a borrower defaulting on a loan.

To develop this model, the bank will follow the data science life cycle, which includes the following steps:

Business Understanding: In this phase, the bank will identify the business problem and determine how the model will be used to address it.

Data Understanding: The bank will examine the historical data (provided in a train.csv file) to understand the characteristics and trends of the data. They will also use the test.csv file, which contains unseen data, to evaluate the model.

Data Preparation: In this phase, the bank will clean and prepare the data for analysis and modeling. This may include missing value imputation, normalization, and feature engineering.

Modeling: The bank will use both AutoML (using the auto-sklearn library) and traditional machine learning techniques (using the sklearn library) to train a range of models and compare their performance. They will also use sweetviz, an autoEDA tool, to conduct exploratory data analysis.

Evaluation: The bank will evaluate the performance of the trained models using various metrics, such as accuracy and correlation coefficients.

Deployment: Once the most promising model has been identified, the bank will deploy it in their home loan application process to improve the speed and accuracy of creditworthiness assessments.
