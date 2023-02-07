# linear-regression
1.Define machine learning; what are the differences between machine learning and normal programming?
Machine learning is a subfield of artificial intelligence, which is broadly defined as the capability of a machine to imitate intelligent human behavior. Artificial intelligence systems are used to perform complex tasks in a way that is similar to how humans solve problems,,,,Traditional programming is a manual process—meaning a person (programmer) creates the program. But without anyone programming the logic, one has to manually formulate or code rules.
In machine learning, on the other hand, the algorithm automatically formulates the rules from the data.
Machine Learning Programming
Unlike traditional programming, machine learning is an automated process. It can increase the value of your embedded analytics in many areas, including data prep, natural language interfaces, automatic outlier detection, recommendations, and causality and significance detection. All of these features help speed user insights and reduce decision bias.


2. Answer is => 1=> Supervised ML>>Learns by using labelled data ,Type of problems(Regression and classification),Algorithmsl likes (Linear Regression, Logistic Regression, SVM)
2=> Un Supervised ML>>Trained using unlabelled data without any guidance. ,Type of problems(Clustering),Algorithmsl likes (PCA, KNN,K – Means)
3=> Reinforcement ML>>Works on interacting with the environment ,Type of problems(Exploitation or Exploration), Algorithms likes (Q – Learning,
SARSA)
4=>Semi-supervised learning=> is a type of machine learning. It refers to a learning problem (and algorithms designed for the learning problem) that involves a small portion of labeled examples and a large number of unlabeled examples from which a model must learn and make predictions on new examples


3.Clustering is Un Supervised , and Classification is  Supervised .

4.What is Gradient Descent? Do you know any other thing similar to it?
Answer is Gradient descent is an optimization algorithm which is commonly-used to train machine learning models and neural networks. Training data helps these models learn over time, and the cost function within gradient descent specifically acts as a barometer, gauging its accuracy with each iteration of parameter updates..the other is L-BFGS optimization,,Levenberg-Marquardt algorithm (LMA) optimization,,Simulated Annealing optimization.

 5. You're approximating a function f(x) = wx+b, you have the data points x
 1. What is w? 
 2. What is x?
 3. What is $b$?
 4. Why is x written inbold-face in the question, what does it mean?
 5. How are you planning to get the values of $w
 
 answer=>
        1.Slope ,Rate of predicated for y for each unit increases of x 
        2.The features / inputs / variables
        3.The intercept / level of y when x = 0
        4.that's mean x will be vector not single value..
        5. To estimate w and b, we solve for the w and b that minimize this objective function. This can be
         done by setting the derivatives to zero and solving.
 
  6. $w:=w - \alpha \frac{1}{m}\sum_{i =1}^{m}(f_{w, b}(x^{(i)} )- y^{(i)}) x^{(i)}$
  1. What is$\alpha$? 
  2. What is $m$?
  3. What is $y$?
  4. What does the summation compute?
 
  Answer=>
          1. Learning rate and it esed to  scale the magnitude of parameter updates during gradient descent
          2. number of trainig examples 
          3. actual value of an observation
          4. The summation compute the partial derivatives ...
           
# Bonus NumPy Questions:-
 1.What does np.cumsum calculate?
      Answer:- cumsum() function is used when we want to compute the cumulative sum of array elements over a given axis.
 2.What do np.argmin and np.argmax calculate?
  Answer :- The numpy. argmin() method returns indices of the min element of the array in a particular axis. 
            The numpy. argmax() method returns indices of the max element of the array in a particular axis. 
 
 3.How to rotate a matrix 90?
  Answer:- np.rot90
 4.What do np.arange and np.newaxis do?
  Answer :- np.arange  Return Value and Parameters of np. arange()
                       start is the number (integer or decimal) that defines the first value in the array.=>0
                       stop is the number that defines the end of the array and isn't included in the array.=5 doesn't include
 
            The np. newaxis is generally used with slicing. It indicates that you want to add an additional dimension to the array.
            
5.What's the difference between np.flatten and np.ravel?
Answer :- ravel() Return only reference/view of the original array  ,, If you modify the array you would notice that the value of the original array also changes.
          flatten() Return copy of the original array ,,   If you modify any value of this array value of the original array is not affected.
          
6.1=>>> array([0. , 0.2, 0.4])        
          
  2=>>> array([0.]) 
          
          
          
          
          
 
 
 
 
 
 
 
 
 
 
 
