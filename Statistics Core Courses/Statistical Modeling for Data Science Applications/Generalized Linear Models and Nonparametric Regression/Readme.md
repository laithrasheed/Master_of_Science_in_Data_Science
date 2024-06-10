![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

# Generalized Linear Models and Nonparametric Regression [<sup>[1]</sup>](#reference-1)				

## Brief Description

- Generalized Linear Models and Nonparametric Regression teaches generalized linear models (GLMs), which provide an introduction to classification (through logistic regression); nonparametric modeling, including kernel estimators, smoothing splines; and semi-parametric generalized additive models (GAMs). Emphasis will be placed on a firm conceptual understanding of these tools. Attention will also be given to ethical issues raised by using complicated statistical models.


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

### Week 1   |  An Introduction to Generalized Linear Models Through Binomial Regression

In this module, we will introduce generalized linear models (GLMs) through the study of binomial data. In particular, we will motivate the need for GLMs; introduce the binomial regression model, including the most common binomial link functions; correctly interpret the binomial regression model; and consider various methods for assessing the fit and predictive power of the binomial regression model.

#### Learning Objectives

- State the assumptions required for the correct application of standard linear regression (covered in course 1).
- Describe how to generalize the linear model framework to accommodate data that is not suitable for the standard linear regression model.
- Describe why a standard linear regression model will not work well for binomial data.
- Identify the three components of GLMs: an exponential family response variable, a linear predictor and link function.
- Describe two important link functions associated with binomial regression.
- Derive the likelihood function for binomial regression and describe how it is used in parameter estimation.
- Interpret the parameters that show up in binomial regression with the logistic link function.
- Analyze binomial data in R.
- Explain how feedback loops arise in statistical modeling; articulate some ethical issues that arise from these feedback loops.
- Describe why the basic process of variable measurement is not as straightforward as it might at first seem; articulate some ethical issues that arise from difficulties related to measurement.
- Analyze the components of the “machine learning loop” and articulate its relevance to statistical modeling.
- Describe how statistical and machine learning models can lead to demographic disparities.
- Articulate the tradeoffs between human judgement and judgements made by statistical models.

#### Programming Assignment

- Peer Reviewed and Programming Assignments

### Week 2 |  | Models for Count Data

In this module, we will consider how to model count data. When the response variable is a count of some phenomenon, and when that count is thought to depend on a set of predictors, we can use Poisson regression as a model. We will describe the Poisson regression in some detail and use Poisson regression on real data. Then, we will describe situations in which Poisson regression is not appropriate, and briefly present solutions to those situations.

#### Learning Objectives

- Analyze count data in R.
- Diagnose overdispersion, and adjust the binomial regression model to deal with overdispersion.
- Define the Poisson regression deviance and Chi-squared statistics, and utilize them to assess the fit of the binomial regression model.
- Interpret the parameters that show up in the Poisson regression model.
- Derive the likelihood function for Poisson regression and describe how it is used in parameter estimation.
- Describe three important components of the Poisson regression model.
- Identify situations in which Poisson regression would be appropriate.

#### Programming Assignment

- Peer Reviewed and Programming Assignments 

### Week 3   |  Introduction to Nonparametric Regression

In this module, we will introduce the concept of a nonparametric regression model. We will contrast this notion with the parametric models that we have studied so far. Then, we’ll study particular nonparametric regression models: kernel estimators and splines. Finally, we will introduce additive models as a blending of parametric and nonparametric methods.

#### Learning Objectives

- Compare and contrast nonparametric smoothing methods.
- Implement and interpret the loess smoother in R.
- Write the objective function (function to be minimized) in smoothing spline regression, and describe how this function strikes a balance between goodness of fit and smoothness of the solution.
- Describe smoothing splines as an alternative to kernel estimation.
- Implement kernel smoothing in R and interpret the results.
- Describe the sensitivity of the kernel estimator as a function of bandwidth and choice of kernel.
- Define the bandwidth (smoothing parameter) in kernel estimation and describe the role that it plays.
- Define a kernel in the context of kernel estimation/smoothing, and be able to identify important kernels used in kernel estimators.
- Define a kernel estimator as a nonparametric regression technique.
- Articulate the advantages and disadvantages of nonparametric statistical models.
- Define parametric and nonparametric statistical models.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments  

### Week 4 |  Introduction to Generalized Additive Models

Some models, such as linear regression, are easily interpretable, but inflexible, in that they don't capture many real-world relationships accurately. Other models, such as neural networks, are quite flexible, but very difficult to interpret. Generalized additive models (GAMs) are a nice balance between flexibility and interpretability. In this module, we will further motivate GAMs, learn the basic mathematics of fitting GAMs, and implementing them on simulated and real data in R.

#### Learning Objectives

- Interpret partial regression plots for GAMs in R.
- Interpret the inference-related output from the R implementation of GAMs.
- Implement and interpret GAMs in R using the mgcv package.
- Describe the smoothing splines approach to fitting GAMs.
- State some advantages and disadvantages of (generalized) additive models.
- Describe how an additive model can incorporate linear terms, and describe advantages of doing so.
- Describe how an additive model can be generalized to incorporate non-normal response variables (i.e., define a generalized additive model).
- Define an additive model, and describe how it differs from the most general form of the multivariate regression model.
- Describe the motivation for studying generalized additive models.

#### Programming Assignment

-  Peer Reviewed and Programming Assignments   


### Week 5 |  Final Exam

You will complete a proctored exam worth 20% of your grade made up of multiple choice questions. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### Proctored Exam


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5013)
