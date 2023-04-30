# Online Payments Fraud Detection

The introduction of online payment systems has helped a lot in the ease of payments. But, at the same time, it increased in payment frauds. Online payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting online payment fraud is very important for credit card companies to ensure that the customers are not getting charged for the products and services they never paid.

To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud.

Below are all the columns from the dataset I’m using here:

1. step: represents a unit of time where 1 step equals 1 hour
2. type: type of online transaction
3. amount: the amount of the transaction
4. nameOrig: customer starting the transaction
5. oldbalanceOrg: balance before the transaction
6. newbalanceOrig: balance after the transaction
7. nameDest: recipient of the transaction
8. oldbalanceDest: initial balance of recipient before the transaction
9. newbalanceDest: the new balance of recipient after the transaction
10. isFraud: fraud transaction


# Project Details

This project uses several technologies to develop an online payments fraud detection model. The primary programming language used is Python, with the help of various libraries such as Pandas, NumPy, Plotly Express, Seaborn, and Matplotlib for data processing, analysis, and visualization. The Scikit-Learn library is used for implementing the Decision Tree Classifier algorithm, which is used to build the fraud detection model.

The project follows a step-by-step approach, starting with importing the necessary libraries, loading the dataset, and performing exploratory data analysis to gain insights into the data. This includes visualizing the distribution of transaction types, transforming categorical features into numerical, checking the correlation between the features of the data, and splitting the data into training and test sets.

The next step involves training the fraud detection model using the Decision Tree Classifier algorithm. The model is trained on the training set, and its accuracy is evaluated using the test set. The model is then used to classify whether a transaction is a fraud or not by feeding the transaction features into the model.

This solution has a wide range of real-world applications, as online payments are becoming more prevalent. Fraudulent transactions are a major concern in the online payments industry, and this model can help identify fraudulent transactions and prevent financial losses. For example, financial institutions can use this model to monitor transactions in real-time and flag any suspicious transactions for further investigation. This can help prevent fraud and improve the overall security of online payments.