# Machine-Learning-Algorithms
Testing Machine learning Algorithms with various datasets using python libraries.

Video Link: https://github.com/Suresh-Garimella/Machine-Learning-Algorithms/blob/main/Naive%26SVM_Recording.mkv

1. Find the correlation between ‘survived’ (target column) and ‘sex’ column for the Titanic use case in class.

 Do you think we should keep this feature?
 Yes , we should keep this feature.

Correlation is a statistical term which in common usage refers to how close two variables are to having a linear relationship with each other.
And Features with high correlation are more linearly dependent and hence have almost the same effect on the dependent variable. So, when two features have high correlation, we can drop one of the two features. correlation values are b/w -1 to +1.
Justification:- The Correlation value for the features "Survived" and "Sex" is -0.543351380657755.
But in our senario the correlation is inversely proportional between two features are not completely correlated to each other.
which means each one has their fair share in predicting the output from the machinelearning model.

2. Which algorithm you got better accuracy? Can you justify why?
   Naive Bayes gives the accuracy of 0.837 (83%) where as SVM gives the accuracy as 0.697(69%).
   So, from the output we need to choose Naives Bayes Algorithm over SVM.
   justification:-
         ->Naïve Bayes is a supervised machine learning algorithm used for classification problems. It is built on Bayes Theorem. It is called Naïve because of its Naïve                   assumption of Conditional Independence among predictors.
          ->It assumes that all the features in a class are unrelated to each other.
          *SVM is more powerful to address non-linear classification tasks. SVM generalizes well in high dimensional spaces like those corresponding to texts. It is              effective with more dimensions than samples. It works well when classes are well separated.
          
          From Correlation we know that not all values are well separated so we can know that Naive Bayes is best for this type of data. 
