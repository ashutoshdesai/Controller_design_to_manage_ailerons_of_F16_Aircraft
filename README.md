# Controller_design_to_manage_ailerons_of_F16_Aircraft

Objective: Predict the command to be issued to the controller based on the status of the airplane. The features in the dataset represent the airplane's status.

Key concepts/methods used:
1. Implement the direct solution to linear regression on the training set. Report the root-mean-square error (RMSE) for both the training and validation sets.
2. Implement gradient descent for linear regression using a fixed learning rate, and by iterating until your model's validation RMSE converges. Here we will consider it converged once validation RMSE is within 0.1% of the Direct Solution RMSE.
3. Using GD method, change the batch size with constant learning rate and observe results.
4. Using GD method, change the learning rate with constant batch size and observe results.
5. Implement an adaptive learning rate scheme where you start a mini-batch gradient descent with a large learning rate and decrease the learning rate while you are getting closer to the local minima. It's up to you to come up with a way to set when and how much do you want to change the learning rate. 

OUR GOAL IS TO FIND A METHOD (OR A COMBINATION OF PARAMETERS), TO ACHIEVE FASTEST CONVERGENCE.
