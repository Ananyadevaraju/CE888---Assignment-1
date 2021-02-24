# CE888---Assignment-1
Project proposal - Bias in Machine Learning Algorithms

Abstract:
Machine learning algorithms are being used across various domains with the aim of reducing human prejudice in decision making. For these algorithms to be reliable, it is crucial for its predictions to be unbiased and transparent. The machine learning models can learn bias from the data compiled by humans or from the assumptions made while training them. Therefore, it is important to detect and mitigate bias at various stages of building these models. In this study, different metrics are used for detecting algorithmic bias against race and gender in police arrests. In addition, application of pre-processing, in-processing and post-processing techniques to reduce bias at different stages of designing the models are studied to attain fairness in algorithms. 

Data:
The data for stop,question and frisk for the year 2019 in New York is obtained from https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page .

Aim:
The objective is to detect whether sensitive features like gender and race of the subject determines the outcome, arrest or no arrest. In addition, fairness techniques are used to mitigate the observed bias, to make the model more reliable.

Dependencies:
* Python - version 3.6, 3.7
* scikit learn
