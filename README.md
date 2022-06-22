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

![image](https://user-images.githubusercontent.com/75427257/175016418-d0a44b21-7140-4943-8540-17fad938a04f.png)




 


