Won't answer all of them, just pick some useful ones

1. Can you name four types of problems where it shines.
  - regression
  - classification
  - visualization
  - find rules

2. What are the two most common supervised tasks
  - regression
  - classification

3. What type of ML algorithm would you use to allow a robot to walk in various unknown terrains?
   I assume the robot can only move to different direction. If it makes a wrong decision, it will get punishment. So reinforcement learning is suitable.
   
4. What is an online learning system?
   An online learning system can learn incrementally. It accepts new data continuous and trains on very large data.

5. What is the difference between a model parameter and a learning algorithm's hyperparameter.
   Hyperparameter can't be learned during the process of modeling training. E.g., `k` of KNN can only be predefined and optimized by grid/random search.

6. If your model performs gerat on the training data but generalizes poorly to new instances, what is happening? Can you name 3 possible solutions.
   This is a problem of overfitting which caused by lack of training data. 3 possible solutions are: 1. Getting more training data; 2. Add regularization factor to simplify the model; 3. Cross validation 4. Reduce the noise in the training data

7. What is the purpose of test set and validation set.
   Test set is used to estimate the generalization error that a model will make on new instances.  A validation set is used to compare models. It makes it possible to select the best model and tune hyperparameters. Another explain is, test set is just for testing. It is invisible for the whole training process. However, we can't select models based on training errors. In this case, we split a set from the observed data and use it as `fake test set` to evaluate different models.