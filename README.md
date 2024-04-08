# Optimizing Bank Marketing Strategies: A Comparative Analysis of Classification Models for Predicting Term Deposit Subscription

Implement and analyze various Machine Learning algorithms: 

1. Decision Trees 
2. Random Forests 
3. Boosting 
4. Logistic Regression


Problem Statement: Develop and compare classification models to predict client subscription to a term deposit based on bank marketing attributes. Identify the most effective algorithm and provide actionable insights for optimizing marketing strategies.

Data Description:

I used bank-full.csv.

a. This dataset has 45211 entries, each with 17 inputs, ordered by date (older version of this dataset with less inputs). First 16 inputs for each entry are attributes and 17th input is the class to be predicted.

b. Out of 16 attributes, 7 attributes (age, balance, day, duration, campaign, pdays and previous) are numeric. Rest are categorical (including binary attributes).

Following are the attributes of this dataset (with brief description): bank client data:

age (numeric)

job: type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services")

marital: marital status (categorical: "married", "divorced", "single"; note: "divorced" means divorced or widowed)

education (categorical: "unknown","secondary","primary","tertiary")

default: has credit in default? (binary: "yes","no")

balance: average yearly balance, in euros (numeric)

housing: has housing loan? (binary: "yes","no")

loan: has personal loan? (binary: "yes","no") related with the last contact of the current campaign:

contact: contact communication type (categorical: "unknown", "telephone", "cellular")

day: last contact day of the month (numeric)

month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")

duration: last contact duration, in seconds (numeric) other attributes:

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)

previous: number of contacts performed before this campaign and for this client (numeric)

poutcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success") 

Output variable (desired target): has the client subscribed a term deposit? (binary: "yes","no")


Reference github: https://github.com/prakhardogra921/Bank-Marketing-Classification/blob/master/1.ipynb
