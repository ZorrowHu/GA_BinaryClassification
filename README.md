# GA_BinaryClassification
## GA_KMeans
Combination of Genetic Algorithm and K-Means. Genetic Algorithm performs feature selection while K-Means takes advantages of the selected features to make better classification.
## GA_LDA
Similar to GA_KMeans, it is a combination of Genetic Algorithm and LDA, which means LDA is used to make classification predictions.
## Reference
[For more algorithm details and helpful source code, please see](https://blog.csdn.net/Mr_Lowbee/article/details/86566949)
# Output
## GA
For two different classification methods, K-Means and LDA, the output of GA remains the same.
As is shown below, the selected best individuals' fitness from genetic evolution declines with the growth of feature dimension. However, it is roughly experimented that both K-Means and LDA performs their best when feature dimension is around 30. 
![](https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/Dimension-Fitness.png)

GA evolves torward better fitting individuals which means population's fitness should show a growing pattern, which is convinced by the figure below.

![](https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/Iteration-Fitness.png)
## K-Means
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-1.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-2.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-3.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-4.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-5.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-6.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-7.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-8.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-9.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-10.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-11.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-12.png" height="150"/>
<img src="https://github.com/ZorrowHu/GA_BinaryClassification/blob/master/photos/K-Means-13.png" height="150"/>
