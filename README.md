Modelled version of a car that will learn how to drive itself. And the key word here is learn,because the car will not be given any rules on how to operate in the environment before hand - it will have to figure everything out on it's own using Deep Q-Learning.

Deep Q-Learning is the result of combining Q-Learning with an Artificial Neural Network. The states of the environment are encoded by a vector which is passed as input into the Neural Network. Then the Neural Network will try to predict which action should be played, by returning as outputs a Q-value for each of the possible actions. Eventually, the best action to play is chosen by either taking the one that has the highest Q-value, or by overlaying a Softmax function.

