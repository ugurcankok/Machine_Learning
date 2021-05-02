# Machine Learning Repository

You can look at my work on Machine Learning in this repository.

In this repository, you will find my works in ***src*** folder:

* ### [0. Data Preprocessing](https://github.com/ugurcankok/Machine_Learning/tree/master/src/0.%20Data%20Preprocessing)

  <img src="https://miro.medium.com/max/1400/1*L6vivCP633xS1XAGXJOXlQ.jpeg" width="400" height="200">

  Data preprocessing is a data mining technique that involves transforming raw data into an understandable format. Real-world data is often incomplete, inconsistent, and/or lacking in certain behaviors or trends, and is likely to contain many errors. Data preprocessing is a proven method of resolving such issues.

  #### Machine Learning ProcessSteps in Data Preprocessing
  
  * **Step 1 :** Import the libraries
  * **Step 2 :** Import the dataset
  * **Step 3 :** Check out the missing values
  * **Step 4 :** See the Categorical Values
  * **Step 5 :** Splitting the dataset into Training and Test Set
  * **Step 6 :** Feature Scaling
  
  *You can read **[my blog post](https://medium.com/@ugurcankok0/simple-linear-regression-82863633b607)** on this subject in the Medium.*
 
* ### [1. Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression)

  Regression algorithms fall under the family of Supervised Machine Learning algorithms which is a subset of machine learning algorithms. One of the main features of supervised learning algorithms is that they model dependencies and relationships between the target output and input features to predict the value for new data. Regression algorithms predict the output values based on input features from the data fed in the system. That methodology is the algorithm builds a model on the features of training data and using the model to predict the value for new data.

  * [Simple Linear Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/1.%20Simple%20Linear%20Regression)

    <img src="https://miro.medium.com/max/1280/1*g2Oh7bDCCjvgqwXeWT2UlQ.gif" width="400" height="200">
  
    Simple linear regression is a statistical method that enables users to summarise and study relationships between two continuous (quantitative) variables. Linear regression is a linear model wherein a model that assumes a linear relationship between the input variables (x) and the single output variable (y).
  
    *You can read **[my blog post](https://medium.com/@ugurcankok0/simple-linear-regression-82863633b607)** on this subject in the Medium.*
  
  * [Multiple Linear Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/2.%20Multiple%20Linear%20Regression)

    <img src="https://miro.medium.com/max/1400/1*PK-JI9NGgPYBnaBesfDbCQ.jpeg" width="400" height="200">

    Multiple linear regression attempts to model the relationship between two or more explanatory variables and a response variable by fitting a linear equation to observed data. Every value of the independent variable x is associated with a value of the dependent variable y. The population regression line for p explanatory variables x1, x2, ... , xp is defined.
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/multiple-linear-regression-cdba03e3a072)** on this subject in the Medium.*
    
  * [Polynomial Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/3.%20Polynomial%20Regression)
  
    <img src="https://4.bp.blogspot.com/-rMmdWLNRRcI/WopS4NgG7lI/AAAAAAAAAIQ/OHIx1620HAwjW3KN_gDCHE4OoLZaYR8iQCEwYBhgL/s1600/polreg_ggplot.png" width="400" height="200">
    
    Polynomial Regression is a form of regression analysis in which the relationship between the independent variables and dependent variables are modeled in the nth degree polynomial. Polynomial Regression is a special case of Linear Regression where we fit the polynomial equation on the data with a curvilinear relationship between the dependent and independent variables.
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/polynomial-regression-83e7575c123c)** on this subject in the Medium.*
    
  * [Support Vector Regression (SVR)](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/4.%20Support%20Vector%20Regression%20(SVR))
  
    <img src="https://i.pinimg.com/736x/3b/c5/3c/3bc53ced72ff0ecf225c948a75bc481a.jpg" width="400" height="250">
    
    Support Vector Regression is a type of Support Vector Machine that supports linear and non-linear regression. As it seems in the below graph, the mission is to fit as many instances as possible between the lines while limiting the margin violations. The violation concept represents as ε (epsilon). Main idea is always: to minimize error, individualizing the hyperplane which maximizes the margin, keeping in mind that part of the error is tolerated.
    
  * [Decision Tree Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/5.%20Decision%20Tree%20Regression)

    <img src="https://miro.medium.com/max/1204/1*YRMpKm--tjZ1TGNhmBLDOA.png" width="400" height="250">
    
    Decision tree builds regression or classification models in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. A decision node has two or more branches, each representing values for the attribute tested. Leaf node represents a decision on the numerical target. The topmost decision node in a tree which corresponds to the best predictor called root node. Decision trees can handle both categorical and numerical data. 
    
     *You can read **[my blog post](https://medium.com/@ugurcankok0/decision-tree-regression-688f9f44670a)** on this subject in the Medium.*
     
  * [Random Forest Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/1.%20Regression/6.%20Random%20Forest%20Regression)

    <img src="https://miro.medium.com/max/1378/1*4nZ4kKsi1z_mihWQWFb_Fg.jpeg" width="400" height="250">
    
    Random forest is an ensemble of decision trees. This is to say that many trees, constructed in a certain “random” way form a Random Forest. Each tree is created from a different sample of rows and at each node, a different sample of features is selected for splitting. Each of the trees makes its own individual prediction. These predictions are then averaged to produce a single result.
    
     *You can read **[my blog post](https://medium.com/@ugurcankok0/random-forest-regression-72d41bcbe596)** on this subject in the Medium.*

* ### [2. Classification](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification)

  Classification is a process of categorizing a given set of data into classes, It can be performed on both structured or unstructured data. The process starts with predicting the class of given data points. The classes are often referred to as target, label or categories. The classification predictive modeling is the task of approximating the mapping function from input variables to discrete output variables. The main goal is to identify which class/category the new data will fall into.

  * [Logistic Regression](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/1.%20Logistic%20Regression)

    <img src="https://miro.medium.com/max/920/1*jWRFYaUEPaAMZMLqtdtCHQ.png" width="400" height="250">
    
    Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/logistic-regression-958c0e591c7d)** on this subject in the Medium.*

  * [K-Nearest Neighbors (K-NN)](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/2.%20K-Nearest%20Neighbors%20(K-NN))

    <img src="https://miro.medium.com/max/1182/1*U9dOThJUekSHmdXrsSbr_A.png" width="400" height="250">
    
    K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique. K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/k-nearest-neighbors-65c3f46b891b)** on this subject in the Medium.*
    
  * [Support Vector Machine (SVM)](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/3.%20Support%20Vector%20Machine%20(SVM))

     <img src="https://www.tutorialspoint.com/scikit_learn/images/marginal_hyperplane.jpg" width="400" height="250">
     
     The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points. To separate the two classes of data points, there are many possible hyperplanes that could be chosen. Our objective is to find a plane that has the maximum margin, i.e the maximum distance between data points of both classes. Maximizing the margin distance provides some reinforcement so that future data points can be classified with more confidence. Hyperplanes are decision boundaries that help classify the data points. Data points falling on either side of the hyperplane can be attributed to different classes.

  * [Kernel SVM](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/4.%20Kernel%20SVM)

    <img src="https://miro.medium.com/max/838/1*gXvhD4IomaC9Jb37tzDUVg.png" width="400" height="250">
    
    We already know that SVM is a supervised machine learning algorithm used to deal with both classification and regression problems. Compared to the other classification and regression algorithms, the svm approach is completely different. Kernel plays a vital role in classification and is used to analyze some patterns in the given dataset. They are very helpful in solving a no-linear problem by using a linear classifier. Later the svm algorithm uses kernel-trick for transforming the data points and creating an optimal decision boundary. Kernels help us to deal with high dimensional data in a very efficient manner. 
    
    
  * [Naive Bayes](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/5.%20Naive%20Bayes)

    <img src="https://miro.medium.com/max/1400/1*vdX3TJ8u_8F4dSdT5Csz3g.png" width="400" height="250">
    
    Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other. Naive Bayes model is easy to build and particularly useful for very large data sets. Along with simplicity, Naive Bayes is known to outperform even highly sophisticated classification methods. Bayes theorem provides a way of calculating posterior probability P(c|x) from P(c), P(x) and P(x|c).
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/naive-bayes-classification-ed47383d4a99)** on this subject in the Medium.*
    
  * [Decision Tree Classification](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/6.%20Decision%20Tree%20Classification)

    <img src="https://miro.medium.com/max/1400/1*htzLqpLyTYBx0spAIHGpsw.png" width="400" height="250">
    
    Decision tree builds classification or regression models in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. A decision node has two or more branches. Leaf node represents a classification or decision. The topmost decision node in a tree which corresponds to the best predictor called root node. Decision trees can handle both categorical and numerical data. 
    
    *You can read **[my blog post](https://medium.com/@ugurcankok0/decision-tree-classification-48efda20b04f)** on this subject in the Medium.*

  * [Random Forest Classification](https://github.com/ugurcankok/Machine_Learning/tree/master/src/2.%20Classification/7.%20Random%20Forest%20Classification)

    <img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2020/02/rfc_vs_dt1.png" width="400" height="250">
    
    Random forests is a supervised learning algorithm. It can be used both for classification and regression. It is also the most flexible and easy to use algorithm. A forest is comprised of trees. It is said that the more trees it has, the more robust a forest is. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance. Random forests has a variety of applications, such as recommendation engines, image classification and feature selection.

* ### [3. Clustering](https://github.com/ugurcankok/Machine_Learning/tree/master/src/3.%20Clustering)

  * [K-Means Clustering](https://github.com/ugurcankok/Machine_Learning/tree/master/src/3.%20Clustering/1.%20K-Means%20Clustering)
  * [Hierarchical Clustering](https://github.com/ugurcankok/Machine_Learning/tree/master/src/3.%20Clustering/2.%20Hierarchical%20Clustering)
  
* ### [4. Project](https://github.com/ugurcankok/Machine_Learning/tree/master/src/4.%20Project/Movie%20Recommendation)
  
  * [Movie Recommendation](https://github.com/ugurcankok/Machine_Learning/tree/master/src/4.%20Project/Movie%20Recommendation)
