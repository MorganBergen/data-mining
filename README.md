#  introduction to data mining

####  contents

1.  [description](##description)
2.  [outline](##outline)
3.  [topics](##topics)
4.  [grading](##grading)

###  description

**textbook**  [introduction to data mining, by pang-ning tan, michael steinbach, anuj karpatne, vipin kumar, isbn: 0133128903, 2018](https://www-users.cse.umn.edu/~kumar001/dmbook/index.php)

data mining studies the algorithms and computational paradigms that allow computers to discover knowledge and perform decision automatically using large and complex datasets.  in this course, we will explain the fundamental principles, technical details, and real life applications of data mining techniques through lectures, case studies, and course projects.  the core topics to be covered include data preproprocessing, classification, cluster analysis, association analysis, anomaly detection, neural networks, model evaluation, and applications like recommernder systems.   the learning goals are to think sysematically of how data mining can solve analytical problems, to make better infromed decisions using various real-world data.  as well as understand data mining process, algorithm development, and system deign to build a pathway to the career of a data scientist.


##  schedule

###  august 21 2023 [introduction to data mining](./00-intro.md)

**covers**  what is the challenge and why should we do data mining.  what is data mining:  definition, process, and examples.  data mining tasks:  classification, clustering, association rules, anomaly detection

###  august 25 2023 [data](./01-data.md)

**reading**  chapter 2.1 types data

**reading**  chapter 2.2 data quality

**covers**  continue on introduction of association rules, anomaly detection

###  august 28 2023 [data](./02-data.md)

**reading**  

chapter 2.3  data preprocessing

chapter 2.4  measures of similarity and dissimilarity

**covers**  

-  data preprocessing -  aggregation, samping, dimensionality reduction, feature selection, feature creature, discretization and binarization, attribute transformation

###  september 01 2023 [data](./03-data.md)

**reading**  

chapter 2.4  measures of similarity and dissimilarity

**covers**  

-  general distance and similarity - euclidean and monkowski distance.  smc / jaccard and cosine similarity, pearson's correlation.  information based measures - mutual information, kl-divergence.  ranking distance.  distance of sets of data point

###  september 04 2023 [decision tree classifier](./04-decision.md)

**reading**

chapter 3.1 basic concepts

chapter 3.2 general framework for classification

chapter 3.3 decision tree classifier

**covers**
-  supervised learning setup - regression, classification.  decision tree - goal, algorithm, split, criterion, node impurity (gini index)

###  september 08 2023 [decision tree classifier](./05-decision.md)

-  **chapter 3.4**  olap and multidimensional data analysis
-  **chapter 3.5**  model selection
-  decision tree - node impurity (entrypy, misclassification error)
-  split for continuous attributes
-  model overfitting - definition, example, generalization error, model pruning

###  september 11 2023 [evaluation metrics](./06-evaluation.md)

-  python and pandas tutorial code
-  **chapter 3.6** model evaluation
-  **chapter 3.7** presence of hyper parameters
-  chapter 3.8
-  evaluation and metrics for classification models - confusion matrix, accuracy, precision, recall, F-measure, roc, auc, corss-validation
-  tutorial of developing data mining project and setting up python enviroment using conda

###  september 15 2023 [logistic regression](./07-logistic.md)

-  scikit-learn tutorial: code
-  chapter 4.6
-  linear regression review - model, sum of squared errors loss function, gradient descent optimization
-  logistic regression classifier - model, cross-entropy loss function, regularization

###  september 18 2023 [naive bayes classifier](./08-naivebayes.md)
###  september 22 2023 [bayesian network, k-nearest neighbor classifiers](./09-bayesian-knn.md)
###  september 25 2023 [support vector machine (SVM)](./10-svm.md)
###  september 29 2023 [neural networks](./11-neuralnet.md)
###  october 02 2023 [neural networks](./12-neuralnet2.md)
###  october 06 2023 [midterm review](./13-midterm-review.md)
###  october 09 2023 [midterm exam (part 1)](./14-midterm1.md)
###  october 13 2023 [midterm exam (part 2)](./15-midterm2.md)
###  october 16 2023 [no class due to fall break](./16-fallbreak.md)
###  october 20 2023 [neural networks](./17-neuralnet3.md)
###  october 23 2023 [clustering & k-means](./18-clustering.md)
###  october 27 2023 [hierarchical clustering](./19-hierarchical.md)
###  october 30 2023 [DBSCAN & cluster evaluation](./20-dbscan.md)
###  november 03 2023 [association rule mining](./21-association.md)
###  november 06 2023 [association rule mining](./22-association2.md)
###  november 10 2023 [association rule mining](./23-association3.md)
###  november 13 2023 [association rule mining](./24-association4.md)
###  november 17 2023 [anomaly detection](./25-anomaly.md)
###  november 20 2023 [deep learning framework](./26-deeplearning.md)
###  november 24 2023 [no class due to thanksgiving break](./27-thanksgiving.md)
###  november 27 2023 [ensemble methods and boosting](./28-ensemble.md)
###  december 01 2023 [final review](./29-finalreview.md)
###  december 06 2023 [data mining application: recommender systems](./30-recommender.md)
###  december 08 2023 [stop day](./31-stopday.md)


###  outline

####  1.  introduction
-  why big data?  what is big data mining?  why data mining?  data mining processes, relation to budiness intelligence techniques
-  introduction to data mining tasks (classification, clustering, association analysis, anomaly detection).  what is a model?  basic terminologies, predictive modeling
-  real world data mining applications

####  2.  data and preproprocessing
-  understanding of data, what is data?  type of attributes, properties of attribute values, types of data, data quality
-  sampling, data normalization, data cleaning, similarity measures
-  feature selection / instance selection, the importance of feature selection / instance selectin in various big data scenarios 

####  3.  classification
-  decision-tree based approach (e.g. C4.5)
-  rule-based approach (e.g. Ripper)
-  instance based classifiers (e.g. k-nearest neighbor)
-  support vector machines (svms)
-  ensemble learning
-  classification model selection and evaluation
-  applications: b2b customer buying stage prediction, recommender systems

####  4.  association analysis
-  apriori algorithm and its extensions
-  association pattern evaluation
-  sequantial patterns and frequent subgraph mining
-  applications:  b2b customer buying path analysis, medical informatics, telecommunication alarm diagnosis

####  5.  clustering
-  partitional and hierarchical clustering methods
-  graph based methods
-  density based methods
-  cluster validation
-  applications:  customer profiling, market segmentation

####  6.  anomaly detection
-  statistical based and density based methods

####  7.  neural networks
-  neorons and network topology
-  multi layer feed forward network

####  8.  data mining case studies
-  big data analytics in mobile enviroments
-  fraud detection and prevention with data mining techniques
-  big data analystics in real world business

###  grading

| unit                      | weight        |
|:--------------------------|:--------------|
| exam 1                    | 20%           |
| exam 2                    | 20%           |
| programming project       | 20%           |
| assignments               | 30%           |
| attendance                | 10%           |


