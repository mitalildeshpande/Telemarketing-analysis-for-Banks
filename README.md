# Telemarketing-analysis-for-Banks

Banking institutions earn money in many ways and Term deposits are considered one of the major sources for the same. 
Telephonic marketing is one of the best ways to reach out to people at large to inform and attract them for term deposits. 
Though, in order to do this, huge expenses need to be directed towards the setting up of call centers. It is ineffective and expensive 
to keep calling the same target audience every time when we are unsure whether they will apply for the term.
To overcome the above-mentioned problem, based on the previous data collected, we can figure out the collective of people interested 
in making a term deposit considering a variety of factors like age, education, etc. 
This way, a lot of resources like time and money can be saved and can effectively attract a larger set of audiences.

The dataset used is of a Portuguese banking institution from UCI Machine Learning repository and is related to telephonic marketing campaigns. 
It can be seen from the dataset that the same target audience was to be called repeatedly to check if he/she has subscribed to a term deposit or not. 
The dataset consists of about 45,000 rows and 18 columns and is over a period of two years.

At first, I performed data pre-processing and Exploratory data analysis (EDA). 
Under pre- processing I performed outlier detection, label encoding, checked if any NULL, duplicates values are present etc. 
With EDA, I got insights into our dataset using Histogram, Scatter plot, Correlation, Heat maps, etc.

Later, applied various classifiers like SVM, KNN, Gradient Boost, Random Forest to classify whether a customer will make a term deposit or not and used evaluation metrics like confusion matrix, precision, recall, classification report, ROC curve and AUC for the analysis. Gradient boost gave the highest accuracy of 90.68%.

Developed a web application with Gradio where we entering the client details it will help us check if that client will opt for a term deposit plan or not.
Gradio is an open-source Python library which allows you to develop an easy-to-use customizable component demo for your ML model.

