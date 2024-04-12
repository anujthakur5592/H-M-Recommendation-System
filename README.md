# H&M Recommendation System


This H&M recommendation system project has been successful in achieving the goals of giving customers personalized recommendations, enhancing their shopping experience, and boosting the company's sales.

# Introduction
-To conduct Exploratory Data Analysis on clothing data and selected relevant features for clothing item prediction
-To build a Pipeline through Pyspark to accelerate data processing.
-To compare the performance of different Recommendation Models: ALS and LGBM Ranker.
-To deliver comparison analysis on the effect of scaling and to gain exposure to advanced big data tools.

-There are mainly 3 parts in this technique:
1) Data Description
2) Data Processing Pipeline
3) Applied Models and Model Results
 
<img width="398" alt="Picture1" src="https://github.com/anujthakur5592/H-M-Recommendation-System/assets/166769513/42743d02-acfe-462d-8a51-530987de70fc">

# Data Description
- DTotal No of customers: 1371980 
- No of customers who made at least one transaction: 1362281.
- % of customers who made at least one transaction: 99.29306549658158.
- Number of customers who did not make a purchase: 9699.
- % of customers who did not make a purchase: 0.7069345034184238.
- It seems that not all customers made a purchase, there is around 1% with no purchase history.
- This file is used to convert image dimensions from (784,1) to (28,28) and to display those images.

# Disclaimer
- Alternating Least Square (ALS) is also a matrix factorization algorithm and it runs itself in a parallel fashion. ALS is implemented in Apache Spark ML and built for large-scale collaborative filtering problems. ALS is doing a pretty good job at solving the scalability and sparseness of the Ratings data, and it’s simple and scales well to very large datasets.
Some high-level ideas behind ALS are
- Its objective function is slightly different than Funk SVD: ALS uses L2 regularization while Funk uses L1 regularization.
-This technique can also be used for different types of noise as well as different variations of each noise.
-Its training routine is different: ALS minimizes two loss functions alternatively; It first holds the user matrix fixed and runs gradient descent with the item matrix; then it holds the item matrix fixed and runs gradient descent with the user matrix. Its scalability, ALS runs its gradient descent in parallel across multiple partitions of the underlying training data from a cluster of machines. 
![Untitled](https://github.com/anujthakur5592/H-M-Recommendation-System/assets/166769513/fe377eaa-f3a9-4e15-b827-453646a2531a)

# Conclusion
- Major Outcome:

In conclusion, this H&M recommendation system project has been successful in achieving the goals of giving customers personalized recommendations, enhancing their shopping experience, and boosting the company's sales.

This project’s ability to precisely predict customer preferences and make pertinent product recommendations is made possible using cutting-edge ALS algorithms models, and data analytics techniques. 


- Future Approach:

The H&M recommendation system has, in general, showing how technology has the potential to enhance customer engagement and motivate business growth in the fashion retail sector.

Therefore, this project helps to design and implement a recommendation system that could accurately predict customer preferences and suggest relevant products, ultimately increasing customer engagement and driving business growth for H&M.
