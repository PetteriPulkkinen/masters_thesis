- We are interested of the predictability of measurements
- The predictability is measured with:
 1. Error covariance matrix that is calculated from the model
 2. Innovation sequence (likelihood and correlation)

- Mahalanobis distance can be used to calculate "Euclidean distance" from the distribution mean -> if running mean of innovations is much more than zero then something "bad" has happened
- Also it is possible to normalize innovation measurements to supposed to have unit diagonal covariance, and investigate what is happening on those measurements 

1. Set threshold for maximum 