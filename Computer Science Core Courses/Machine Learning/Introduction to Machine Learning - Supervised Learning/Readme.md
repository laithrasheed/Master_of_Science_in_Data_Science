![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

# Introduction to Machine Learning - Supervised Learning [<sup>[1]</sup>](#reference-1)				

## Brief Description

- In this course, we will cover the basics of deep learning, such as multilayer perceptron, convolutional neural network, recurrent neural network, how to build and train neural network models, optimization methods, and application examples.


## Prior knowledge needed: 
##### [Data Science Foundations ](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations)


## Learning Outcomes

- Use modern machine learning tools and python libraries.
- Explain how to deal with linearly-inseparable data.
- Compare logistic regression’s strengths and weaknesses.
- Explain what decision tree is & how it splits nodes.

## Resources

- [ISLR Course Textbook](https://www.statlearning.com/).

## Course Content

### Week 1  | Introduction to Machine Learning, Linear Regression

This week, we will build our supervised machine learning foundation. Data cleaning and Exploratory Data Analysis (EDA) might not seem glamorous, but the process is vital for guiding your real-world data projects. The chances are that you have heard of linear regression before. With the buzz around machine learning, perhaps it seems surprising that we are starting with such a standard statistical technique. In "How Not to Be Wrong: The Power of Mathematical Thinking", Jordan Ellenberg refers to linear regression as "the statistical technique that is to social science as the screwdriver is to home repair. It's the one tool you're pretty much going to use, whatever the task" (51). Linear regression is an excellent starting place for solving problems with a continuous outcome. Hopefully, this week will help you appreciate how much you can accomplish with a simple model like this.

#### Learning Objectives

- Explain and compare each learning type in machine learning.
- Use basic Python libraries such as NumPy, Pandas, and Matplotlib to inspect data and perform exploratory data analysis.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments

### Week 2 | Multilinear Regression

This week we are building on last week's foundation and working with more complex linear regression models. After this week, you will be able to create linear models with several explanatory and categorical variables. Mathematically and syntactically, multiple linear regression models are a natural extension of the simpler linear regression models we learned last week. One of the differences that we must keep in mind this week is that our data space is now 3D instead of 2D. The difference between 3D and 2D has implications when considering how to do things like creating meaningful visualizations. It is essential to understand how to interpret coefficients. Machine learning involves strategically iterating and improving upon a model. In this week's lab and Peer Review, you will identify weaknesses with linear regression models and strategically improve on them. Hopefully, as you progress through this course specialization, you will get better and better at this iterative process.

#### Learning Objectives

- Explain how linear regression model works.
- Compare linear regression’s strengths and weaknesses — when can we apply linear regression and when we should be careful? What are the methods to overcome the issues?
- Use modern machine learning tools and Python libraries — we will introduce the Scikit-learn library’s logistic regression package.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments 

### Week 3  | Logistic Regression

Even though the name logistic regression might suggest otherwise, we will be shifting our attention from regression tasks to classification tasks this week. Logistic regression is a particular case of a generalized linear model. Like linear regression, logistic regression is a widely used statistical tool and one of the foundational tools for your data science toolkit. There are many real-world applications for classification tasks, including the financial and biomedical realms. In this week's lab, you will see how this classic algorithm will help you predict whether a biopsy slide from the famous Wisconsin Breast Cancer dataset shows a benign or malignant mass.

#### Learning Objectives

- Explain how logistic regression model works and when we should use it.
- Compare logistic regression’s strengths and weaknesses — can we apply logistic regression to any binary classification problem?
- Use modern machine learning tools and Python libraries — we will introduce the Scikit-learn library’s logistic regression package.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments  

### Week 4 |  Non-parametric Models: KNN and Decision Trees

This week we will learn about non-parametric models. k-Nearest Neighbors makes sense on an intuitive level. Decision trees are a supervised learning model that can be used for either regression or classification tasks. In Module 2, we learned about the bias-variance tradeoff, and we've kept that tradeoff in mind as we've moved through the course. Highly flexible tree models have the benefit that they can capture complex, non-linear relationships. However, they are prone to overfitting. This week and next, we will explore strategies like pruning to avoid overfitting with tree-based models. In this week's lab, you will make a KNN classifier for the famous MNIST dataset and then build a spam classifier using a decision tree model. This week we will once again appreciate the power of simple, understandable models.

#### Learning Objectives

- Explain what decision tree is and how it splits nodes.
- Calculate gini, entropy and information gain given examples.
- Identify key hyperparameters and their effect on the model performance and models’ bias-variance.
- Explain how pruning works and the role of the cost-complexity parameter.
- Build model and train using sklearn library.
- Demonstrate hyperparameter selection and tuning based on the training results.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments   

### Week 5 | Ensemble Methods

Last week, we learned about tree models. Despite all of the benefits of tree models, they had some weaknesses that were difficult to overcome. This week we will learn about ensembling methods to overcome tree models' tendency to overfit. The winner utilizes an ensemble approach in many machine learning competitions, aggregating predictions from multiple tree models. This week you will start by learning about random forests and bagging, a technique that involves training the same algorithm with different subset samples of the training data. Then you will learn about boosting, an ensemble method where models train sequentially. You will learn about two essential boosting algorithms: AdaBoost and Gradient Boosting. This week, work on the main analysis of your final project. Iterate and improve on your models. Compare different models. Perform hyperparameter optimization. Sometimes this part of a machine learning project can feel tedious, but hopefully, it will be rewarding to see your performance improve.

#### Learning Objectives

- List ensembling methods to increase decision tree performance.
- Compare bagging, RF and boosting on how they work and effect of hyperparameters.
- Build and train models to data, tune hyperparameters.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments 

### Week 6 |  Kernel Method

This week we will be exploring another advanced topic, Support Vector Machines. Don't let the name intimidate you. This week, we will work through understanding this powerful supervised learning model. Hopefully, you will build an intuitive understanding of essential concepts like the difference between hard and soft margins, the kernel trick, and hyperparameter tuning. Next week, you will submit the three deliverables for your final project: the report, video presentation, and a link to your GitHub repository. Suppose you aim to finish iterating on your models, hyperparameter optimization, etc., this week. In that case, next week, you can polish your report, make sure your GitHub repository is ready for Peer Review, and give an excellent presentation of your work.

#### Learning Objectives

- Explain how soft-margin classifier works.
- Explain the role of C parameter.
- Explain how to deal with linearly-inseparable data.
- Apply Scikit-learn SVM model to a dataset: build, train the model and tune hyperparameters

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments 

### Week 7 |  Final Exam

You will complete a peer reviewed final project worth 33% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### [Project Presentation and Documents]()


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5509)
