# Vamshi-portfolio

**About me:** <br />
Hello, my name is Vamshi. The following are my projects in Machine Learning and Finance. I have started to learn ML seperate outside of my University study interests. I am passionate in interdisciplinary learnings from economics, finance, Data Science, and many more. And the following are the projects and my findings.
<br /> <br />
Click on project to review Jupyter notebook code
<br/>
# [Project 1: Titanic survival prediction](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/Titanic3.ipynb)

* Supervised Learning
* Dataset contains features of passengers such as:
  * Name
  * Age
  * Sex
  * etc...
* Cleaned data removing features that did not contribute or irrelevant to the survival of passengers.
* Used scikit-learn logistic regression model to predict the survival of passengers in the test group.
* Uploaded to kaggle and scored 77% accuracy.

# [Project 2: Wine Clustering](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/wineclustering.ipynb)

* Unsupervised Learning
* Principal Component Analysis is used to graph/plot and understand the clusters better.
* For the dataset, MinMax scaling is done in order to get the most optimal cluster points and bring the examples together into a tighter cluster.
* The clusters/scatter plots of data is shown below.

![alt_text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/cluster%20scatter.jpg)

* Dataset contains charactersitics of wines produced in 3 different regions in Italy.
* These wines even though produced in the same region have differnent characteristics, and the KMeans clustering algorithm can be used to classify different types.
* The trained clusters were as follows:

![alt_text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/trained%20clusters.jpg)

* Now, the test of these clusters is shown in the following figure

![alt_text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/test%20clusters.jpg)

# [Project 3: Boston Housing](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/bostonhousing.ipynb)

* Supervised learning
* The goal is to predict the median value of house owner prices given certain features in the dataset.
* A simple linear regression yield good results but looking at the scatter plot of all features against price of the house, it was evident that the relation was polynomial.

![alt text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/boston%20scatterplot.jpg)

* Scatter plot

![alt text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/boston%20histo%20scatter%20plot.jpg)

* Histogram + Scatter plot

![alt_text](https://github.com/vamshikodipaka7/Vamshi-portfolio/blob/main/corelation%20matrix.jpg)

* This is a corelation matrix among the features and their weights. A positive number shows that those combination of features add value to the price while negative says otherwise.

* After testing some linear models, i.e. basic linear regression and regularised and polynomial regression, the best model is choosen according to the best score on the test set.
