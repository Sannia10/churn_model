# Overview

The main aim of this analysis is to build on a report by a company - FoodCorp, which encounters the problem of customer churn. This report tends to use the data available by the company to classify the customers as churners or non-churners, so that preventive action could be taken to stop customers from switching elsewhere. In order to do this, supervised learning techniques were used. Building on the analysis provided by Consulting Corp, it was decided that a customer who does not visit the store(s) within 21 days will be classified as a potential churner. This was primarily done through analyzing the distribution of time between the visits of customers. The input features of the model were constructed based on the number of visits and the quantity bought by the active customers during specific time frames. After the essential steps of feature engineering and preprocessing, 4 different models were constructed. These were evaluated on the basis of several performance metrics and the results suggested that support vector machines classifier (SVM) tends to perform better than the rest of algorithms. Thus, SVM was chosen to be the final choice for training the model.
This report also talks about the distinct behavioral and spending patterns of the churners and the non- churners. The results reveal that churners are more likely to be infrequent, low spending customers, who just visit the stores once in a while to buy necessities. On the other hand, non-churners are consistent buyers who spend on a greater variety of items. They also spend more amount of money on average than the non-churners. The customer insights derived from this report can be used distinguish between churners and non-churners effectively. It can also serve as a basis for devising effective marketing strategy to keep the people engaged.


**Instructions for Python Notebook:**
1.	The code for all the methods tried and tested is included in the jupyter notebook with comments.
2.	The file contains a section at the end named as “Churn Model”. It includes the step by step procedure of extracting the data, defining the features, scaling the data and running the final model.
3.	The code for all the models (Random Forest, SVM etc.) including their temporal hold out evaluation is under their respective headings.
   
**Instructions for Figures:**
1.	Fig 1.1 is created in jupyter notebook. It is a correlation matrix. The code can be found under the feature selection heading.
2.	Fig 2.1, 2.2, 2.3 and 2.4 are created in Tableau using the excel files. The excel files were created in python under the section “Customer Insights. These files were imported into Tableau to create the graphs.
3.	The figures of confusion matrix of all models as well as the classification reports are made in python. Seaborn library has been used to create the confusion matrix and sklearn metrics were used to generate the classification report.
   
**Instructions for Excel Files:**
1.	The excel file named “ucd_data” has been created as a result of an SQL query. This file was created to be used for customer insights analysis. The code can be found under the “Customer Insights” section in the python notebook.
2.	The excel files named “data1”, “churners” and “non_churners” were also created to make graphs in tableau. Their codes are also included in the python notebook.

**Data Cleaning:**

No additional data cleaning was undertaken.
