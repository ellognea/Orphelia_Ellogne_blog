---
layout: post
title: What is covariance ?
---

<div align="justify">  
Baking a chocolate cake for 6 people requires specific ingredients and quantities such as 3 large eggs, 6 oz of sugar, 6 oz of flour etc ... If we instead want to bake for 5 people, decreasing the quantity of some ingredients might require changes in the quantity of other ingredients. The direction of the relationship between the ingredients’ quantities is called covariance.
<br>
If two ingredients both increase (decrease) at the same time, their covariance is positive. For example, less flour is required when the number of eggs is reduced. However, if two ingredients vary in opposite direction, their covariance is negative. For instance, less sugar is needed when honey is added to the recipe. Lastly, if two ingredients don’t have any effect on each other (i.e.: if they are independent), their covariance is zero.
</div> 
<br>
<div align="justify">
However, does a 0 covariance imply independence? Let’s say you’re baking a lemon and a chocolate cake. The required sugar quantities are specified in the recipes; hence the covariance between the required amount of sugar in each cake is zero. But, imagine that you don’t have enough sugar for both cakes. This means that the amount of sugar you can add to the lemon cake depends on the quantity you’ll use for the chocolate cake. Therefore, the sugar quantities are not independent. This shows that a 0 covariance does not necessarily imply independence.
<br>
Let’s continue with the baking analogy to explore another characteristic of covariance. If the covariance between eggs and sugar is 3 and the covariance between flour and cocoa powder is 10, can we conclude the latter covariance is stronger than the former? The answer is no. Covariance does not give us the strength of the relationship between two variables because it doesn’t have a minimum and a maximum value (i.e. it is not normalized). Its magnitude depends on the magnitude of the variables.
</div> 
<br>
<div align="justify">
Luckily, it is possible to scale the covariance such that it has a minimum value of -1 and a maximum value of 1. This is done by dividing it by the standard deviations of both variables. Doing so, transforms the covariance into its normalized form called correlation… Nothing is lost though, just transformed.
<br>
In probability and statistics, covariance is formally defined as “the expected product of deviations of two random variables from their mean values” (lab 551, lecture 3). In other words, it tells us whether we should expect one random variable to be below (above) its mean when the other is.
<br>
Covariance plays a key role in data science. Random variables with high covariance can be combined without losing significant information. It is also useful for inferences; it can be used to predict one result from another. In addition, it allows the integration of data from multiple sets which is key to machine learning.
</div> 

<br>

**Source**:
<br>
- Michael Gelbart. (2018). "Descriptive statistics and probability for data science, lecture 3".<https://github.ubc.ca/MDS-2018-19/DSCI_551_stat-prob-dsci_students/blob/master/lectures/lecture3.ipynb>

- "Statistics how to?".Covariance in statistics: what is it?Example. Read on September 14, 2018 from <http://www.statisticshowto.com/covariance/>

- Ruslana Dalinina. "Oracle+ Datascience.com". Introduction to correlation. Read on September 14, 2018 from <https://www.datascience.com/blog/introduction-to-correlation-learn-data-science-tutorials>

- Brian Stacey."Quora". What is the purpose of covariance in statistics ? How does it differ from correlation? Read on September 14,2018 from  <https://www.quora.com/What-is-the-purpose-of-covariance-in-statistics-How-does-it-differ-from-correlation>

- Brian Quanz."Quora". What are the applications of data science. Read on September 14, 2018 from <https://www.quora.com/What-are-the-applications-of-covariance>

- Alan Anderson "dummies". How to measure the covariance and correlation of data samples. Read on September 14, 2018 <https://www.dummies.com/education/math/business-statistics/how-to-measure-the-covariance-and-correlation-of-data-samples/>

- Stack exchange. What is covariance in plain language. Read on September 14, 2018 from <https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language>


