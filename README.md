# CST_383_Titanic_Project
We are using Titanic dataset to answer: 

What age ranges are likely to survive?
Are women or men more likely to survive?
Higher or lower class more likely to survive?

Report Guidelines


Introduction 10%

Why was the project undertaken?
What was the research question, the tested hypothesis or the purpose of the research?

We have taken up this project in order to, study the various demographics of the people onboard the Titanic, determine how various factors influenced their survival. These factors include age, gender, and class. Since these factors typically have strong effects on how an individual is viewed in society, this project can show how these factors may or may not still have held influence in a chaotic situation such as this.


Selection of Data 20%

What is the source of the dataset? Characteristics of data?

Any munging or feature engineering?

We sourced our CSV file from Kaggle, which had about 890 samples whom were passengers of the Titanic. The dataset has several attributes, which range from passenger ID, to Age, to whether or not the passenger survived. We mainly used the Sex, Age, Pclass (Passenger Class) and Survived columns to compute our predicitons.

Data Munging:

We dropped the cabin column as there were too man N/A values; additionally, we inserted the male mean ages and the female mean ages into the N/A values in the age column as to get a more comprehensive predicition, as Age is a main component in our predicition. Additionally, we assigned the sex column into a binary composite: male = 1 and female = 0.



Methods 20%

What materials/APIs/tools were used or who was included in answering the research question?

In this project we used pandas to check for missing values. We used scikit for all machine learning models and for preprocessing the Sex column on data set. We preprocessed with SciKit's label encoder to change male and female to binary representation. We also made use of seaborn to display some data in a graph matrix, distribution plot and scatter plot in our notebook.

As for the collaborative environent, we used Google Colaboratory to be able to assigne different tasks, run code and review data that was presented.
Results 20%

What answer was found to the research question; what did the study find? Was the tested hypothesis true? Any visualizations?


Discussion 20%

What might the answer imply and why does it matter? How does it fit in with what other researchers have found? What are the perspectives for future research? Survey about the tools investigated for this assignment.


Summary

Most important findings.


Kaggle link: https://www.kaggle.com/c/titanic/data
