# Predicting Breast Cancer Using Molecular Cell Data and Machine Learning Classifiers

## Introduction
Our topic is pertinent to the diagnosis of breast cancer from multivariate cellular properties (such as breast tissue cell uniformity and shape). Our data is composed of 546 patient samples sourced from clinical trial at the University of Wisconsin; 212 cases attain malignancy and 357 are benign.

As per articles published by the National Institute of Health, the usage of machine learning in cancer detection is still experimental; however, an increasing number of hospitals (post 2005) have reported that “algorithmic processing” (a mixture of ML and AI) has successfully caught the onset of the disease in nearly 25 percent of cases (Crus & Wishart, 2007). Historic patient data, when classified particularly by ethnicity, age, and prior personal medical record, can be strategized as input for ML models that aim to predict the existence of cancer in a given individual (Tran et al., 2021). Strides in computer vision, a related field, have gained traction in supplementing numerical/categorical quantifiers (the primary inputs to established ML models) with object recognition capacities in pictorial data (Alfain et al., 2022). 

## Motivation
Breast cancer is the most prevalent form of the disease in women. However, given that its symptoms mirror those of significantly less concerning ailments, successful diagnosis typically occurs in advanced stages of the illness. Therefore, developing an ML model that aids the early diagnosis of breast cancer (with high accuracy) is advantageous. 

## Methods
We will implement supervised classifiers to classify the (predicted) presence of cancer (or lack thereof) via logistic regression, Naive Bayes, and random forest; doing so will enable us to probabilistically estimate the occurrence of cancer emergence based on aggregated patient cell inputs. Random forest, in particular, will be of great use, as its creation of decision trees (each formed from a subset of independent training data) will be formidable against error and noise. To encapsulate unsupervised learning, we will facilitate agglomerative clustering (pointedly single linkage). Computing the (shortest) distances among similar data points (and thereafter establishing larger, merged clusters) will allow us to discern which biometric inputs are most alike and grasp the reasoning behind our supervised results to a heightened degree. 

## Results and Discussion
We plan to classify whether or not a woman has breast cancer.  To evaluate each classification method we will use quantitative metrics to determine the amount of error and accuracy of each method. For each method, we will consider Mean Squared Error, R-Squared Value, and Cross Entropy Loss. Mean Squared Error will give us a good indicator of how biased and variable our models are. R-Squared value will inform us if there are any strong or weak correlations present between the input and output. Cross Entropy Loss will help us adjust model weights during training until we can minimize changes in our model.

## References
<p>Alfian, G., Syafrudin, M., Fahrurrozi, I., Fitriyani, N. L., Atmaji, F. T. D., Widodo, T., Bahiyah, N., et al. (2022). Predicting Breast Cancer<br> &nbsp;&nbsp;&nbsp;&nbsp;from Risk Factors Using SVM and Extra-Trees-Based Feature Selection Method. Computers, 11(9), 136. MDPI AG.<br></p>

<p>Cruz, J. A., & Wishart, D. S. (2007). Applications of machine learning in cancer prediction and prognosis. Cancer informatics, 2, 59–77.<br></p>

<p>Tran, K. A., Kondrashova, O., Bradley, A., Williams, E. D., Pearson, J. V., & Waddell, N. (2021, September 27). Deep learning in <br>&nbsp;&nbsp;&nbsp;&nbsp;cancer diagnosis, prognosis and treatment selection - genome medicine. BioMed Central.</p>

## Dataset
[Breast Cancer Wisconsin Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## Gantt Chart
![Gantt Chart](GantChart.png)

## Contribution Table
![Contribution Table](ContributionProposal.png)
