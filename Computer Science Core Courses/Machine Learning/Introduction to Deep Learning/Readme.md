![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

# Introduction to Deep Learning [<sup>[1]</sup>](#reference-1)				

## Brief Description

- In this course, we will cover the basics of deep learning, such as multilayer perceptron, convolutional neural network, recurrent neural network, how to build and train neural network models, optimization methods, and application examples.


## Prior knowledge needed: 
##### [Data Science Foundations ](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations)


## Learning Outcomes

- Explain what multilayer perceptrons, convolutional neural networks and recurrent neural networks are and how they work.
- Build and train neural network models using deep learning libraries such as Keras.
- Tune hyperparameters of a neural network model and an optimizer to improve performance.
- Choose and/or design neural network architectures.
- Explain how optimization and weight update works in neural network training

## Resources

- [ISLR Course Textbook](https://www.statlearning.com/).

## Course Content

### Week 1  | Deep Learning Introduction, Multilayer Perceptron

We are starting off the course with a busy week. This week's module has two parts. In the first part, after a quick introduction to Deep Learning's exciting applications in self-driving cars, medical imaging, and robotics, we will learn about artificial neurons called perceptrons. Interestingly, neural networks are loosely modeled on the human brain with perceptrons mimicking neurons. After we learn to train a simple perceptron (and become aware of its limitations), we will move on to more complex multilayer perceptrons. The second part of the module introduces the backpropagation algorithm, which trains a neural network through the chain rule. We will finish by learning how deep learning libraries like Tensorflow create computation graphs for gradient computation. This week, you will have two short quizzes, a Jupyter lab programming assignment, and an accompanying Peer Review assignment. This material, notably the backpropagation algorithm, is so foundational to Deep Learning that it is essential to take the time necessary to work through and understand it.

#### Learning Objectives

- Explain how perceptron works and how their weights are updated.
- List activation functions and their definitions, properties.
- List MLP hyperparameters.
- Explain how training works with MLP.
- Calculate gradients in a computational graph.
- Understand how to navigate the course

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments

### Week 2 |  Training Neural Networks

Last week, we built our Deep Learning foundation, learning about perceptrons and the backprop algorithm. This week, we are learning about optimization methods. We will start with Stochastic Gradient Descent (SGD). SGD has several design parameters that we can tweak, including learning rate, momentum, and decay. Then we will turn our attention to advanced gradient descent methods like learning rate scheduling and Nesterov momentum. Besides vanilla gradient descent, other optimization algorithms include AdaGrad, AdaDelta, RMSprop, and Adam. We will cover general tips to reduce overfitting while training neural networks, including regularization methods like dropout and batch normalization. This week, you will build your DL toolkit, gaining experience with the Python library Keras. Assessments for the week include a quiz and a Jupyter lab notebook with an accompanying Peer Review.

This assignment is your last Jupyter lab notebook for the course. For the next three weeks, you will build hands-on experience and complete weekly mini-projects that incorporate Kaggle challenges.

#### Learning Objectives

- Explain how gradient descent works.
- Apply different optimization methods while training and explain different behavior.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments 

### Week 3  | Deep Learning on Images

This module will teach a type of neural network called convolutional neural networks, suitable for image analysis tasks. We will learn about definitions, design parameters, operations, hyperparameter tuning, and applications. There is no Jupyter lab notebook this week. You will have a brief quiz and participate in a clinically relevant Kaggle challenge mini-project. It is critical to evaluate whether cancer has spread to the sentinel lymph node for staging breast cancer. You will build a CNN model to classify whether digital pathology images show that cancer has spread to the lymph nodes. This project utilizes the PCam dataset, which has an approachable size, with the authors noting that "Models can easily be trained on a single GPU in a couple of hours, and achieve competitive scores." As you prepare for the week, look over the rubric and develop a plan for how you will complete it. It will be necessary for a project like this to work on a timeframe that allows you to run experiments. The expectation is not that you will cram the equivalent of a final project into a single week or that you need to have a top leaderboard score to receive a good grade for this project. Hopefully, you will have time to achieve some exciting results to show off in your portfolio.

#### Learning Objectives

- Explain how convolution works.
- List CNN model architectures and functions of their modules.
- Explain factors that impacted the development of the CNN models.
- Use cloud tools and deep learning libraries to implement CNN architecture and train for image classification tasks.
- Tune hyperparameters by applying learned concepts.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments  

### Week 4 | Deep Learning on Sequential Data

This module will teach you another neural network called recurrent neural networks (RNNs) to handle sequential data. So far, we have covered feed-forward neural networks, including Multi-layer Perceptrons and CNNs. However, in biological systems, information can flow backward and forwards. RNNs do a backward pass closer to biological systems. Using RNNs has excellent benefits, especially for text data, since RNN architectures reduce the number of parameters. We will learn about the vanishing and exploding gradient problems that can arise when working with vanilla RNNs and remedies for those problems, including GRU and LSTM cells.

We don't have a quiz this week, but we have a Kaggle challenge mini-project on NLP with Disaster Tweets. The project is a Getting Started competition designed for learners building their machine learning background. The challenge is very doable in a week, but make sure to start early to run experiments and iterate a bit.

#### Learning Objectives

- Explain how RNN works.
- Compare RNN, LSTM, GRU in their mechanism and explain how added features improve performance.
- Apply deep learning package to sequential data, build models, train, and tune.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments   
 
### Week 5 | Unsupervised Approaches in Deep Learning

This module will focus on neural network models trained via unsupervised Learning. We will cover autoencoders and GAN as examples. We will consider the famous AI researcher Yann LeCun's cake analogy for Reinforcement Learning, Supervised Learning, and Unsupervised Learning. Supervised Deep Learning has had tremendous success, mainly due to the availability of massive datasets like ImageNet. However, it is expensive and challenging to obtain labeled data for areas like biomedical images. There is great motivation to continue developing unsupervised Deep Learning approaches to harness abundant unlabeled data sources. This week is the last week of new course material. There is no quiz or Jupyter notebook lab. Generative adversarial networks (GANs) learn to generate new data with the same statistics as the training set. This week, you will wrap up one final Kaggle mini-project. This time, you will experiment with creating a network to generate images of puppies. Keep running experiments and working on the primary analysis for your final project. Ideally, it would be excellent to finish experimenting and iterate with your models this week so that next week, you can focus on preparing your final project deliverables.

#### Learning Objectives

- Explain what autoencoders and how it helps the model to learn features better.
- Explain what GAN is and how it works.
- Explains what challenges in training GANs.
- Tune hyperparameters in training.

#### Programming Assignment

- Quiz, Peer Reviewed, and Programming Assignments   

### Week 6 |  Final Exam

You will complete a peer reviewed final project worth 45% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### [Project Presentation and Documents]()


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5511)
