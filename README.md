# machine_learning + ML Interview Questions

# Machine Learning Interview Questions
A collection of technical interview questions for machine learning Engineer position based on my day-to-day experience with real problems.


#### 1) Do you think that knowing the internal workings of ML algorithms is an advantage over someone who only applies them ?

The main advantage of knowing the ML algorithms in depth is that, unlike other traditional algorithms, you can influence them with, for example,
the hyper parameters or through the way of interpreting them.

#### 2) Could you give an example of the previous question justifying your answer ?

Let's imagine a classical algorithm like the sorting algorithm. whether or not you know how the algorithm works inside, 
you have no influence on the result. Now let´s think about and ML algorithm like Logistic regression. A user who knows howthe algorithm works
can try to move the threshold to obtain better results, in this case the way to interpret the agorithm knowing that it uses a Sigmoid function and that by
default the cutoff is 0.5 but that we can move it, we gives an advantage over someone who doesn´t know how it works.

#### 3) **Situation:** You arrive at a new project as the new ML Engineer, the project tries to identify potential clients who are going to buy a product and whos emails
were free customers registered in a conference. Your boss tells you that he has an algorithm that currently has an accuracy of 80% and aks if you can improve it. How do you act ?

We have thousands of free customers registering in our website every week. 
The call center team wants to call them all, but it is imposible, so they ask me to select those with good chances to be a buyer (with high temperature is how we refer to them). 
We don't care to call a guy that is not going to buy (so precision is not important) but for us is very important that all of them with high temperature are always in my selection, 
so they don't go without buying. That means that my model needs to have a high recall, no matter if the precision goes to hell.

#### **Situation:** You work on a classification algorithm, one of the dataset attributes has a very high cardinality Would this be a problem to have it in your dataset ?
What problem could keep them in your algorithm? and how do you act ?	

**Accuracy**: how many cases you got right (TP+TN) out of the total number of cases (TP+FP+FN+TN).  
**Precision**: how many positives there actually are (TP) among the identified positives (TP+FP).  
**Recall (aka Sensitivity)**: how many positives you have found (TP) out of all those actually positive (TP+FN).  
**Specificity**: how many you have identified as healthy (negative) out of those actually healthy (TN+FP).  
With this in mind, we should be cautious when choosing a metric to optimise in order to calibrate our test correctly.  


Do we want to make sure we don't miss any unidentified patients? `Recall`.
Do we want overall certainty, no matter which way you go wrong? `Accuracy`.
Do we want to focus on identifying the healthy? `Specificity`.
Don't want to alarm anyone with false positives? `Precision`.

#### 4) NLP: What is known as "bag of words"
the vector representation of a document with respect to the corpus.
i.e  "Tea is life. Tea is love." and "Tea is healthy, calming, and delicious." as our corpus. 
The vocabulary then is {"tea", "is", "life", "love", "healthy", "calming", "and", "delicious"}

v1 = [2,2,1,1,0,0,0,0]


#### 5) Can you give an example of a qualitative Feature nominal and ordinal ? 


 Nominal:  Gender, country, fruit .. ( they do not really have a oder)
 Ordinal:  Age ( baby, young, adult, ancient)
           Energy(tire, fine, full energy) --> there is a kind of Order 
 
#### 6) Can you give an example of a Quantitative Feature? 
  Discrete: 1,2,3,4 (values are fix)
  continuous: distance in km os some travel, or weight of someone.


#### 7) What is know as loss in ML ?  
The difference between predicted and actual results. We would be interested to take the model with less loss function.

#### 8) EDA. What advantages do you see to a visualisation of data in EDA ? why should it be a good idea ? 

 - If we have a classification problem, it may be a good idea to visualise the data because if the data is completely randomly distributed (white noise) it will not be possible to do any classification. If, on the other hand, when we do our visualisation we see that there are classes that are clearly differentiated, then it is possible that our ML algorithm will also be able to differentiate the classes.
 
 - Purely informative, the best example would be Anscombe´s Quartet where all the data have the same metrics but are totally different datasts but with the same metrics.




