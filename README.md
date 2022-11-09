# Final High School Project - Classification of Asteroids by Their Hazardousness Using Machine Learning

https://colab.research.google.com/drive/1GVJJRD8co00HTvZR4MGgCuvXk4GJVPwP?usp=sharing
### Written in May 2022, translated in November 2022
Original (in Serbian): https://docs.google.com/document/d/1wDHWRDH_Umnl520aYOkryrJvd-AfeDaV/edit
# **Introduction**


Although interplanetary space is seemingly empty, there are asteroids, comets, or meteorites in it. These objects are united under the name "near-Earth objects, NEOs". There number of comets and asteroids is equal among "near-Earth objects", but comets only account for approximately 1% of the total risk to Earth. Therefore, in this paper, the potential hazardousness of asteroids was analyzed using machine learning methods.

Machine learning is used to improve computers for problem solving by learning from experience. It combines knowledge from computing and statistics and is considered as one of the most current technical fields today. The availability of data that can be used for machine learning enables the intensive development and application of machine learning in a large number of fields, including astronomy.[2] This makes it a suitable method for working with a large amount of asteroid data.

The dataset used in this work is the "NASA: Asteroid Classification" dataset compiled by CNEOS (Center For Near Earth Object Studies). Data analysis and processing as well as machine learning algorithms for the classification of asteroids in relation to their danger were implemented in the Python programming language in the Google Colab environment. The Pearson correlation method, ANOVA and LASSO hybrid method and Random Forest method were used to select the independent variables used in the analysis. Furthermore, with the selected 6 attributes, training and testing was carried out using 10 different methods.

This paper provides an overview of different machine learning algorithms and their application in this analysis. The most successful algorithm on this dataset is Voting Classifier which combines Decision Tree Classifier, Ada Boosting Decision Tree Classifier, and Bagging Decision Tree Classifier models. The success of this algorithm on training data is 100% while its success on testing data is 99.85%.
