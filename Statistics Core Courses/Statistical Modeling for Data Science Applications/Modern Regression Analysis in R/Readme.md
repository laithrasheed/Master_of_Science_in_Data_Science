![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

# Modern Regression Analysis in R [<sup>[1]</sup>](#reference-1)				

## Brief Description

- Modern Regression Analysis in R provides foundational statistical modeling tools for data science. Introduction to methods, theory, and applications of linear statistical models, covering the topics of parameter estimation, residual diagnostics, goodness of fit, and various strategies for variable selection and model comparison. Attention will also be given to the misuse of statistical models and ethical implications of such misuse.


## Prior knowledge needed: 
##### [Statistical Inference](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations/Statistical%20Inference)


## Learning Outcomes

- Acquire, clean, wrangle, and manage data.
- Correctly perform exploratory data analyses in order to assist with the generation of scientific hypotheses.
- Apply principles and methods of probability theory and statistics to draw rational conclusions from data.
- Construct an appropriate statistical model in order to answer important scientific or business-related questions.
- Assess the validity of a statistical model when applied to a particular dataset.
- Be sensitive to ethical issues that are involved in dealing with data science applications arising in real world situations.
- Clearly communicate the results of a data science analysis to a non-technical audience.
- Use peer feedback, self-reflection and video analysis to improve collaboration skills.
- Create reproducible statistical workflows.
- Act ethically in the role of professional data scientist.

## Resources

- Course Material

## Course Content

### Week 1   | Introduction to Statistical Models

In this module, we will introduce the basic conceptual framework for statistical modeling in general, and linear statistical models in particular.

#### Learning Objectives

- Recognize research questions that can be answered using statistical modeling techniques, including linear regression models.
- Define important components of the linear regression model, including predictor and response variables.
- Define and state the importance of concept validity and operationalization.
- Write the multiple linear regression (MLR) model (using matrix-vector notation) and articulate the assumptions necessary for the proper use of MLR models.
- Interpret important components of the MLR model, including the “systematic” and “random” components of the model.
- Interpret the MLR model parameters, and describe how these parameter interpretations contribute toward answering important research questions.
- State cases in which the MLR model would not be an appropriate tool for answering research questions of interest.
- State the importance of simulated data in statistics and data science.
- Simulate data for use in regression modeling.

#### Programming Assignment

- Peer Reviewed and Programming Assignments

### Week 2 | Linear Regression Parameter Estimation

In this module, we will learn how to fit linear regression models with least squares. We will also study the properties of least squares, and describe some goodness of fit metrics for linear regression models..

#### Learning Objectives

- Identify least squares as the method for fitting the linear regression model parameters.
- State the assumptions necessary for performing least squares.
- Write down and calculate (in R) the least squares solution for MLR.
- Describe the conditions under which the least squares solution is equivalent to the maximum likelihood estimator.
- State and interpret the Gauss-Markov theorem.
- Define the hat matrix, fitted values, and residuals for the MLR model.
- Define the Residual Sum of Squares (RSS), Explained Sum of Squares (ESS), and Total Sum of Squares (TSS) for the MLR model. Identify these sums of squares graphically in the case of simple linear regression.
- Compute an estimate of the variance of the error term.
- Define and interpret the coefficient of determination and identify common misinterpretations.
- Define identifiability, describe how non-identifiability arises, and how we might fix the problem of non-identifiability.

#### Programming Assignment

- Peer Reviewed and Programming Assignments 

### Week 3  |  Inference in Linear Regression

In this module, we will study the uses of linear regression modeling for justifying inferences from samples to populations.

#### Learning Objectives

- Motivate the importance of statistical inference in regression analysis.
- Write and interpret the sampling distribution of the MLR least squares estimators; explain why the estimators have a distribution, and why it’s normal.
- Conduct individual t-tests on MLR parameters.
- Explain the motivation for the F-test (and why it is problematic to conduct multiple t-tests).
- Describe how the F-distribution arises (i.e.,ratio of chi-squared random variables).
- Conduct the overall F-test.
- Conduct the partial F-test.
- Calculate confidence intervals for the MLR parameters.
- Interpret MLR results (e.g., standard errors, t-values, p-values) computed in R.
- Conduct hypothesis tests, compute confidence intervals in R, and interpret the results.
- Calculate confidence intervals for the mean of the response in an MLR model.
- Articulate some recommended practices for ethical behavior and communication in statistics and data science.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments  

### Week 4 | Prediction and Explanation in Linear Regression Analysis

In this module, we will identify how models can predict future values, as well as construct confidence intervals for those values. We will also explore the relationship between statistical modelling and causal explanations.

#### Learning Objectives

- Predict the response given a new set of predictors from a fitted MLR model using a point estimate.
- Predict the response given a new set of predictors from a fitted MLR model using an interval estimate (prediction interval).
- Articulate the difference between a prediction interval for the response at a new value for the predictor and a confidence interval for the mean response at a new value for the predictor.
- Correctly distinguish between cases that require prediction intervals and cases that require confidence intervals.
- Compute prediction intervals for the response and confidence intervals for the mean in R.
- Articulate what could go wrong with predictions using MLR.
- Describe and identify the difference between explanatory modeling and predictive modeling.
- Articulate the counterfactual definition of causality and describe some difficulties with this definition.
- Describe the difference between a designed experiment and an observational study. Articulate how you might learn about causality with each.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments   
 
### Week 5 | Regression Diagnostics

In this module, we will learn how to diagnose issues with the fit of a linear regression model. In particular, we will use formal tests and visualizations to decide whether a linear model is appropriate for the data at hand.

#### Learning Objectives

- State the MLR assumptions necessary for using ordinary least squares (OLS) in order of importance.
- State the MLR assumptions necessary for making inferences about the MLR model.
- Construct and interpret plots of the fitted/predicted response against the observed response to assess the linearity assumption.
- Construct and interpret plots of the residuals against the fitted values assess the linearity assumption.
- Construct and interpret plots, such as residual vs index/time plots and successive residual plots, to assess the independence/uncorrelated errors assumption.
- Articulate and implement possible solutions to violations of the uncorrelated errors assumption, including generalized least squares.
- Understand how the residuals of the MLR model do not have constant variance, even under the constant variance assumption.
- Construct and interpret plots of the residuals against the fitted values to assess the constant variance assumption.
- Describe and implement solutions to the problem of nonconstant variance (e.g., transformations and weighted least squares).
- Construct and interpret plots, such as QQ-plots and residual plots, to assess the normality assumption.
- Describe and apply formal tests (e.g., the Shapiro-Wilk test) and graphical summaries to decide whether the residuals are normally distributed.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments

### Week 6 | Model Selection and Multicollinearity

In this module, we will study methods for model selection and model improvement.. In particular, we will learn when and how to apply model selection techniques such as forward selection and backward selection, criterion-based methods, and will learn about the problem of multicollinearity (also called collinearity).

#### Learning Objectives

- Explain the need for model selection methods.
- Describe and implement testing-based procedures for model selection (backward selection, forward selection, and bidirectional selection) and select a “best” model based on a given procedure.
- Describe and implement criterion-based procedures for model selection (AIC, BIC, adjusted R squared) and select a “best” model based on a given procedure.
- Describe how each criterion-based procedure balances modelfit/explanatory power with simplicity (number of parameters).
- Identify and implement methods for diagnosing multicollinearity in a dataset.
- Identify and implement methods for fixing the problem of multicollinearity in a dataset.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments

### Week 7 |  Final Exam

You will complete a proctored exam worth 20% of your grade made up of multiple choice questions. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### Proctored Exam


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5011)
