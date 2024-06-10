![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

#   Resampling, Selection, and Splines [<sup>[1]</sup>](#reference-1)				

## Brief Description

- Consists of the foundational framework & application of cross-validation, bootstrapping, dimensionality reduction, ridge regression, lasso, GAMs and splines.


## Prior knowledge needed: 
##### [Statistical Inference](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations/Statistical%20Inference)


## Learning Outcomes

- Apply resampling methods in order to obtain additional information about fitted models.
- Optimize fitting procedures to improve prediction accuracy and interpretability.
- Understand the benefits and approach of non-linear models.

## Resources

- Course Material

## Course Content

### Week 1    | Welcome and Review

Welcome to our Resampling, Selection, and Splines class! In this course, we will dive deep into these key topics in statistical learning and explore how they can be applied to data science. The module provides an introductory overview of the course and introduces the course instructor. 

#### Learning Objectives

- Review how non-parametric regression and GAMs differ from linear regression.
- Review the concept of a generalized linear model, its assumptions, and how it differs from linear regression

#### Programming Assignment

- Programming Assignments

### Week 2 |  Generalized Least Squares

In this module, we will turn our attention to generalized least squares (GLS). GLS is a statistical method that extends the ordinary least squares (OLS) method to account for heteroscedasticity and serial correlation in the error terms. Heteroscedasticity is the condition where the variance of the errors is not constant across all levels of the predictor variables, while serial correlation is the condition where the errors are correlated across time or space. GLS has many practical applications, such as in finance for modeling asset returns, in econometrics for modeling time series data, and in spatial analysis for modeling spatially correlated data. By the end of this module, you will have a good understanding of how GLS works and when it is appropriate to use it. You will also be able to implement GLS in R using the gls() function in the nlme package. 

#### Learning Objectives

- Describe how GLS extends the OLS method to account for heteroscedasticity and serial correlation.
- Use R to estimate the GLS coefficients and interpret the results.
- Evaluate the performance of GLS compared to OLS for a given dataset, and explain the reasons for any differences.

#### Programming Assignment

- Programming Assignments 

### Week 3   |  Shrink Methods

In this module, we will explore ridge regression, LASSO, and principal component analysis (PCA). These techniques are widely used for regression and dimensionality reduction tasks in machine learning and statistics.

#### Learning Objectives

- Describe the differences between ridge regression, lasso regression, and principal component analysis.
- Apply ridge regression to a dataset with a large number of predictor variables and evaluate its effectiveness in reducing overfitting.
- Analyze the impact of different penalty parameters on the ridge regression model and interpret the results.
- Apply lasso regression to a dataset with a large number of predictor variables and evaluate its effectiveness in variable selection and reducing overfitting.
- Apply principal component analysis to a high-dimensional dataset and evaluate its effectiveness in reducing the number of dimensions.

#### Programming Assignment

- Programming Assignments  

### Week 4 | Cross Validation

This week, we will be exploring the concept of cross-validation, a crucial technique used to evaluate and compare the performance of different statistical learning models. We will explore different types of cross-validation techniques, including k-fold cross-validation, leave-one-out cross-validation, and stratified cross-validation. We will discuss their strengths, weaknesses, and best practices for implementation. Additionally, we will examine how cross-validation can be used for model selection and hyperparameter tuning.

#### Learning Objectives

- Identify the steps involved in implementing cross-validation in R programming.
- Analyze the results of cross-validation to compare different statistical learning models.
- Describe how cross-validation helps in assessing the generalization capability of statistical learning models.

#### Programming Assignment

- Programming Assignments 

### Week 5 |   Boostrapping

For our final module, we will explore bootstrapping. Bootstrapping is a resampling technique that allows us to gain insights into the variability of statistical estimators and quantify uncertainty in our models. By creating multiple simulated datasets through resampling, we can explore the distribution of sample statistics, construct confidence intervals, and perform hypothesis testing. Bootstrapping is particularly useful when parametric assumptions are hard to meet or when we have limited data. By the end of this week, you will have an understanding of bootstrapping and its practical applications in statistical learning.

#### Learning Objectives

- Implement basic bootstrapping methods using R programming
- Interpret the results of a bootstrap analysis and understand their implications
- Describe the purpose and benefits of using bootstrapping in statistics

#### Programming Assignment

- Programming Assignments   


### Week 6 |  Final Exam

You will complete a multiple choice exam worth 25% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### Programming Exam


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5021)
