![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

# Unsupervised Algorithms in Machine Learning [<sup>[1]</sup>](#reference-1)				

## Brief Description

- In this course, we will learn selected unsupervised learning methods for dimensionality reduction, clustering, finding latent features, and application cases such as recommender systems with hands-on examples of product recommendation algorithms.


## Prior knowledge needed: 
##### [Data Science Foundations ](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations)


## Learning Outcomes

- Explain what unsupervised learning is, and list methods used in unsupervised learning.
- List and explain algorithms for various matrix factorization methods, and what each is used for.

## Resources

- [ISLR Course Textbook](https://www.statlearning.com/).

## Course Content

### Week 1  | Unsupervised Learning Intro

Now that you have a solid foundation in Supervised Learning, we shift our attention to uncovering the hidden structure from unlabeled data. We will start with an introduction to Unsupervised Learning. In this course, the models no longer have labels to learn from. They need to make sense of the data from the observations themselves. This week we are diving into Principal Component Analysis, PCA, a foundational dimension reduction technique. When you first start learning this topic, it might not seem easy. There is undoubtedly some math involved in this section. However, PCA can be grasped conceptually, perhaps more readily than anticipated. In the Supervised Learning course, we struggled with the Curse of Dimensionality. This week, we will see how PCA can reduce the number of dimensions and improve classification/regression tasks. You will have reading, a quiz, and a Jupyter notebook lab/Peer Review to implement the PCA algorithm.

#### Learning Objectives

- List unsupervised tasks
- Explain why dimensionality reduction is helpful
- Explain how PCA works
- Demonstrate how to choose right dimension
- Apply PCA to regression or classification tasks using sklearn
- Understand how to navigate the course

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments

### Week 2 | Clustering

This week, we are working with clustering, one of the most popular unsupervised learning methods. Last week, we used PCA to find a low-dimensional representation of data. Clustering, on the other hand, finds subgroups among observations. We can get a meaningful intuition of the data structure or use a procedure like Cluster-then-predict. Clustering has several applications ranging from marketing customer segmentation and advertising, identifying similar movies/music, to genomics research and disease subtypes discovery. We will focus our efforts mainly on K-means clustering and hierarchical clustering with consideration to the benefits and disadvantages of both and the choice of metrics like distance or linkage. We have reading, a quiz, and a Jupyter notebook lab/Peer Review this week..

#### Learning Objectives

- Explain how k-means clustering works
- Explain how hierarchical clustering works
- Apply k-means clustering to data and determine the best k
- Apply hierarchical clustering to data and explain which linkage method works better given dataset

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments 

### Week 3  | Recommender System

This week we are working with Recommender Systems. Websites like Netflix, Amazon, and YouTube will surface personalized recommendations for movies, items, or videos. This week, we explore Recommendation Engines' strategies to predict users' likes. We will consider popularity, content-based, and collaborative filtering approaches, and what similarity metrics to use. As we work with Recommendation Systems, there are challenges, like the time complexity of operations and sparse data. This week is relatively math dense. You will have a quiz wherein you will work with different similarity metric calculations. Give yourself time for this week's Jupyter notebook lab and consider performant implementations. The Peer Review section this week is short.

#### Learning Objectives

- Explain what recommender system is, and examples of its use in industry
- List popular approaches in recommender system and explain what each does
- Explain how collaborative filtering works
- List similarity measures and explain their pros and cons
- Explain how UV decomposition works
- Apply learned concepts to data using python libraries

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments  

### Week 4 |  | Matrix Factorization

We are already at the last week of course material! Get ready for another dense math week. Last week, we learned about Recommendation Systems. We used a Neighborhood Method of Collaborative Filtering, utilizing similarity measures. Latent Factor Models, including the popular Matrix Factorization (MF), can also be used for Collaborative Filtering. A 1999 publication in Nature made Non-negative Matrix Factorization extremely popular. MF has many applications, including image analysis, text mining/topic modeling, Recommender systems, audio signal separation, analytic chemistry, and gene expression analysis. For this week, we focus on Singular Value Decomposition, Non-negative Matrix Factorization, and Approximation methods. This week, we have reading, a quiz, and a Kaggle mini-project utilizing matrix factorization to categorize news articles.

#### Learning Objectives

- Explain what decision tree is and how it splits nodes.
- Calculate gini, entropy and information gain given examples.
- Identify key hyperparameters and their effect on the model performance and models’ bias-variance.
- Explain how pruning works and the role of the cost-complexity parameter.
- Build model and train using sklearn library.
- Demonstrate hyperparameter selection and tuning based on the training results.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments   
 

### Week 5 |  Final Exam

You will complete a peer reviewed final project worth 30% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### [Project Presentation and Documents]()


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5510)
