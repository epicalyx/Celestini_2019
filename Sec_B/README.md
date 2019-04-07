# MACHINE LEARNING PROBLEM

## Multiclass Classification using Support Vector Machine and Back Propagation Neural Network

**Problem Statement:**
Design a machine learning algorithm for finding the zoo for every animal , given the set of features of the animal.

## Setup
### Dataset
The dataset for the problem has been provided in the repository. 
It contains 101 samples. No. of features are 16 and no. of classes of zoo are 7.

### Training
* Support vector machine and Back propagation neural networks are used to classify the animals.Different structural and functional features 
  of animals has been used as features for training the models. A total of 16 features have been fed as input to the models and the output 
  is one-hot-encoded vector for a particular class of zoo.
  
* The SVM model has been tested with different kernels (linear,RBF,polynomial and sigmoid). The BPNN has been tested with different 
  weight initializations and optimizers like Gradient Descent and Adam Optimizer. The BPNN is a fully connected network with 16 nodes 
  in the input layer with each node describing a feature of an animal, hideen layer size is 7 and softmax function is used as the 
  activation function at the output layer since it is a multiclass problem.Cross-entropy loss has been used.
  
* Classification Accuracy and Average Precison Score has been used as the performance metrics.

* KFold validation for validating our dataset with k=5.

* ROC curve is being plotted for all the 4 kernels of SVM.

### Results
**SVM**

Linear Kernel               ![roc curve](https://github.com/epicalyx/Celestini_2019/blob/master/Sec_B/linear_roc.png)
                    


  
  
 
 
 RBF Kernel                 ![roc curve](https://github.com/epicalyx/Celestini_2019/blob/master/Sec_B/rbf_roc.png)
                            
                            
                            


Polynomial Kernel            ![roc curve](https://github.com/epicalyx/Celestini_2019/blob/master/Sec_B/poly_roc.png)
                             
                           
                    


Sigmoid Kernel               ![roc curve](https://github.com/epicalyx/Celestini_2019/blob/master/Sec_B/sigmoid_roc.png)
 
