# Extended-Kalman-Filter


Kalman filters are used to optimally estimate the variables required when they can't be measured directly.


**Approach:**

There are 2 steps:
1) The prediction step and 
2) The Correction step
In the prediction step, we implement the main filter loop, defining the prediction step of the EKF using the motion model provided.
In the correction step, For each landmark measurement received at a given timestep k. Here we firstly compute the measurement model Jacobians at  
xk, then compute the Kalman Gain, then correct the predicted state and correct the covariance.


**Results:**


![unknown](https://user-images.githubusercontent.com/75427257/175014569-a4c86ff8-85c9-412c-ba56-1be45b11e8b0.png)

 


