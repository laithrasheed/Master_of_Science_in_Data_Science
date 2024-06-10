![image](https://github.com/laithrasheed/DTSA5304_Fundamentals_of_Data_Visualization/assets/124019127/031aa6ba-746d-459b-8eb0-3fdde64eac4b)

#   Stability and Capability in Quality Improvement [<sup>[1]</sup>](#reference-1)				

## Brief Description

- In this course, you will learn to analyze data in terms of process stability and statistical control and why having a stable process is imperative prior to performing statistical hypothesis testing. You will create statistical process control charts for both continuous and discrete data using R software. You will analyze data sets for statistical control using control rules based on probability. Additionally, you will learn how to assess a process with respect to how capable it is of meeting specifications, either internal or external, and make decisions about process improvement.

## Prior knowledge needed: 
##### [Statistical Inference](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Data%20Science%20Foundations/Statistical%20Inference)

#### [Statistical Modeling for Data Science Applications](https://github.com/laithrasheed/MSDS_Program_Private/tree/main/Statistics%20Core%20Courses/Statistical%20Modeling%20for%20Data%20Science%20Applications)

## Learning Outcomes

- Understand how to use, select, and interpret process control charts to identify special causes of variation
- Create and interpret control charts for discrete data
- Create and interpret control charts for normal and non-normal distributions
- Analyze the capability of a process to meet customer specifications

## Resources

- Course Material

## Course Content

### Week 1    | Understanding Process Variation, Process Control and Control Charts

In this module, you will learn how to define a process and break it down into components for the purpose of identifying potential sources of variation. You will learn how to classify variation into common and special causes through the use of a control chart. You’ll discover the Taguchi Loss function, and how it relates to the philosophy of quality, and its association to the product control and process control cycles. You will learn the basic anatomy of a control chart as well as the process used to create a control chart, and common errors encountered when using a control chart in practice. You will be able to calculate an appropriate sample size, as well as determine when a process is in control or out of control based on statistical rules.

#### Learning Objectives

- Define a process
- Differentiate between Common Cause and Special Cause Variation
- State the purpose of a control chart
- Discern between conformance to specification and conformance to target
- Differentiate between the Product Control Cycle and Process Control Cycle
- Identify sources of variation with respect to process dominance
- Discern between when to react, and when to leave the process alone
- Describe the anatomy of a control chart
- Describe the 7 step process to create a control chart
- Explain rational subgrouping
- Calculate and select sample size
- Discern between attribute and variables data control charts
- Prepare data for analysis in R
- Identify out of control conditions and patterns on a control chart

#### Programming Assignment


### Week 2 | Xbar and R / Xbar and S Charts / X and MR Charts

In this module, you will learn how to select the appropriate chart given information on sample size and data type. You’ll learn how to create and interpret control charts with subgroups for variables data, as well as how to create them in R. You will also create and interpret control charts with a sample size of one data that is normally distributed. You'll learn how to monitor other statistics using the Individuals and Moving Range Chart. Finally, you will interpret the control charts for statistical control / stability.

#### Learning Objectives

- Create centerlines for the Xbar and R chart
- Estimate the standard deviation from the R chart
- Calculate Control Limits for the Xbar and R chart
- Generate the Xbar and R chart using R software
- Assess the Xbar and R chart for process control
- Create centerlines for the Xbar and S chart
- Calculate Control Limits for the Xbar and S chart
- Estimate the standard deviation from the S chart
- Generate the Xbar and S chart using R software
- Assess the Xbar and S chart for process control
- Understand the limitations associated with X and MR Charts
- Create centerlines for the normally distributed X and MR chart
- Calculate Control Limits for the normally distributed X and MR chart
- Estimate the standard deviation from the MR chart
- Generate the X and MR chart using R software
- Assess the X and MR chart for process control
- Use the X and MR chart to monitor different aspects of variation

#### Programming Assignment

- Programming Assignments 

### Week 3  | X and Moving Range Charts for Non-Normally Distributed Data

In this module, you will learn how to create an X and Moving Range Chart when the underlying distribution is not normally distributed. You’ll learn how to calculate control limits for the X and MR Charts with LogNormal transformed distribution and exponential distribution. Additionally, you will learn how to fit a distribution to the data and calculate control limits associated with the selected distribution. Finally, you will interpret the control charts for statistical control / stability.

#### Learning Objectives

- Recall the 3 approaches for dealing with non-normal distributions
- Select the appropriate test(s) for normality
- Transform non-normal distributions using the Log-Normal transformation
- Calculate the natural tolerance of the transformed distribution and transform it back into the original distribution
- Calculate Control Limits for data that has been transformed
- Generate the X and MR chart using R software for transformed data
- Recognize and test data for exponentiality
- Calculate Control Limits for data that is distributed exponentially
- Calculate Control Limits and Generate the X and MR chart using R software for exponential data
- Identify when distribution fitting must be used
- Perform a goodness of fit test for one distribution
- Perform a goodness of fit test for multiple distributions
- Perform a goodness of fit test for the Johnson distribution
- Calculate Control Limits for data using a fitted distribution
- Generate the X and MR chart using R software for fitted data

#### Programming Assignment

- Programming Assignments  

### Week 4 |  Process Capability

In this module, you will learn how to compare process variation to customer specifications. You’ll learn the three indices associated with capability measures and the three indices associated with performance measures. Additionally, you will learn to assess capability and performance when the data are not normally distributed.

#### Learning Objectives

- Assess capability / performance from a non normal distribution with fitted data
- Assess capability / performance from a non normal distribution with exponentially distributed data
- Assess capability / performance from a non normal distribution with lognormal transformed data
- Assess capability / performance from an X and MR chart for data that is normally distributed
- Assess capability / performance from an Xbar and S chart for data that is normally distributed
- Assess capability / performance from an Xbar and R chart for data that is normally distributed
- Discern between process capability measures and process performance measures
- Relate the Cpm index to the Taguchi Loss Function
- Define the three indices of capability: Cp, Cpk and Cpm
- Differentiate between process control and process capability

#### Programming Assignment

- Programming Assignments 
   
### Week 5 |   Control Charts for Discrete Data

In this module, you will learn how to create and analyze control charts for discrete data. You will learn how to differentiate between data that are Binomial and data that are Poisson distributed in order to select the appropriate control chart. Additionally, you will learn to assess capability using an appropriate discrete probability model.

#### Learning Objectives

- Differentiate between continuous and discrete data
- Select an attribute control chart based on sample size and the underlying distribution
- Calculate a proportion for a sample
- Create centerlines for p chart
- Calculate Control Limits for the p chart using the normal approximation
- Calculate Control Limits for the p chart using the exact calculation
- Generate the p chart using R software
- Assess the p chart for process control
- Calculate an estimate for process capability using p data
- Differentiate between the p chart and np chart
- Calculate np for a sample
- Create centerlines for the np chart
- Calculate Control Limits for the np chart using the normal approximation
- Calculate Control Limits for the np chart using the exact calculation
- Generate the np chart using R software
- Assess the np chart for process control
- Create a Pareto chart
- Calculate an estimate for process capability using np data
- Differentiate between the Binomial and Poisson distributions
- Create centerlines for a c chart
- Calculate Control Limits for the c chart using the normal approximation
- Calculate Control Limits for the c chart using the exact calculation
- Generate the c chart using R software
- Assess the u chart for process control
- Calculate an estimate for process capability using c data
- Calculate u for a sample
- Create centerlines for the u chart
- Calculate Control Limits for the u chart using the exact calculation
- Generate the u chart using R software
- Assess the c chart for process control

#### Programming Assignment

- Programming Assignments 

### Week 6 |  Final Exam

You will complete a multiple choice exam worth 20% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

##### Programming Exam


## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5705)
