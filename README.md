## Toxic Comment Classification Challenge
In this practical assessment, we’ll simulate a Kagglechallenge for classifying the level of toxicity of disrespectful comments in social media.

Kaggle is one of the largest online communities for data scientists and machine learning practitioners. It enables users to find and publish datasets, explore and build Deep Learning models, and collaborate with other data scientists and ML engineers around the world. One of its more interesting features is the Machine Learning Competitions, which attract over a thousand teams and individuals every yeari. These competitions consist of problems posted by companies and/or research institutions in which teams compete to build the best algorithm. Some competitions have prizes in cashii.

Among the most popular Kaggle competitions is the Toxic Comment Classification Challenge. This challenge occurs annually since 2018 and consist of researching and developing methods for detecting and classifying different levels of toxicity in negative and disrespectful online comments, from insults to violent threats. In this assessment, we’ll be using the dataset from the first competition for analysing the performance of different MachineLearning methods for classifying 6 types of toxicity. Details on the dataset and instructions on how to use are available here: Toxic Comment Classification Challenge.

OBS 1: Although the official competition is in groups, this assessment is individual. Additionally, the goal of this activity is not to find the best solution, but to understand the process of evaluating the performance of different Machine Learning algorithms.

OBS 2: It is possible to make late submissions to Kaggle competitions and compare your performance to the leader board resultsiii.

### To complete this assignment
Please carry out the following tasks:

Perform detailed data analysis of the dataset provided by the competition, observing:
Number of sentences and tokens per class (and check if the dataset is unbalanced or not).
Analyse the most common words for each class and, therefore, understand the most used terms for each level of toxicity.
Select three Machine Learning algorithms among the ones listed below(many of these methods were explored in this module and previous ones):
Support Vector Machine (SVM)
K-Nearest Neighbours (KNN)
NaïveBayes
Decision Trees
Logistic Regression
Random Forest
Multi-LayerPerceptron
Analyse their performance in classifying the level of toxicity of different comments. Please make use of the main metrics (accuracy, F1-score, Recall, Precision, and AUC) to compare the different algorithms. Additionally, clearly explain the parameters defined for each model. Any MLpython Library can be used during implementation(such as sklearn and keras).

Consider the main Feature Extraction methods studied in previous Lectures, such as TF-IDF and WordEmbeddings. Using the same three classifier previously analysed, change the Feature Extraction method initially used (for example, if you used Word Embeddings, change to TF-IDF) and repeat the previous experiments and observe if there is any considerable difference between the new results and the previous one (i.e. if the method of feature extraction impacts the classification performance).
Submit your best algorithm to the competition page and check how good it performs in comparison with other groups in the leader board. Discuss the reasons of that performance and what could be done to improve your proposed solution(maximum of two paragraphs).
Submit the final document (in MS-Word or pdf format) containing your responses for sub-tasks 1,2,3, and 4 in the form of a brief report (500 words). Please provide images, graphs, and tables for supporting your data analysis. The Python code must be included in your submission.
