### Fraud-Detection-SQL

The fraud detection project aims to leverage SQL queries to detect anomalies and potential fraud within transactional data. Through data analysis, this initiative enables businesses to unveil suspicious patterns, empowering them to proactively address and mitigate financial risks.

The analysis provides key insights, spotting unusual transaction amounts, detecting suspicious patterns, and flagging potential fraud. It aids in identifying system vulnerabilities, enabling proactive anti-fraud measures

It accomplish three main tasks:

1. [Data Modeling](#Data-Modeling):
Define a database model to store the credit card transactions data and create a new SQL database using your model.

2. [Data Engineering](#Data-Engineering): Create a database schema on SQL and populate your database from the CSV files provided.

3. [Data Analysis](#Data-Analysis): Analyze the data to identify possible fraudulent transactions.

1) Data Modeling

Create an entity relationship diagram (ERD) by inspecting the provided CSV files.
**Note:** For the `credit_card` table, the `card` column should be a VARCHAR(20) datatype rather than an INT.

2) Data Engineering

Using your database model as a blueprint, create a database schema for each of your tables and relationships. Specify data types, primary keys, foreign keys, and any other constraints you defined.

After creating the database schema, import the data from the corresponding CSV files.


3) Data Analysis

Now that your data is prepared within the database, it's finally time to identify fraudulent transactions using SQL and Pandas DataFrames.

4)Challenge

Another approach to identify fraudulent transactions is to look for outliers in the data. Standard deviation or quartiles are often used to detect outliers.

Identifying Outliers based on Standard Deviation

Identifying Outliers based on Interquartile Range
