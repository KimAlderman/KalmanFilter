# KalmanFilter
Udacity Self-Driving Car - Implementation of Kalman filter in Python, and conversion to C++

Self driving cars rely on many inputs (cameras, accelerometers, gyroscopes, etc.). The data generated by the mechanical sensors all have some level of uncertainty though (signal noise). By applying a Kalman filter, we can take the uncertain data and make a very good educated guess about reality. It really is an estimator more than a filter. The Kalman filter assumes that your input data is not a single point but rather a Gaussian distribution. It can predict a current state even if it can't be measured directly.

Matlab has produced four very good videos explaining use for Kalman filter, and the math behind them.

https://www.youtube.com/watch?v=mwn8xhgNpFY

I first implemented a Kalman filter in Python. However, for use in a self-driving car, we need a program that is smaller and faster. Therefore, I converted the filter into C++. 
