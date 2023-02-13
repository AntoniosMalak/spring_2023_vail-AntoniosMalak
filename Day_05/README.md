# Regression Loss Functions

## Topics covered in today's module
* Mean Squared Error
* Mean Absolute Error
* Mean Squared Logarithm Error
* Mean Absolute Percentage Error

## Main takeaways from doing today's assignment
Use mse, mae, msle and mape and discover the difference between them.
- *MSE* Computes the mean of squares of errors between labels and predictions. `loss = square(y_true - y_pred)`
- *MAE* Computes the mean of absolute difference between labels and predictions. `loss = abs(y_true - y_pred)`
- *MSLE* Computes the mean squared logarithmic error between y_true & y_pred. `loss = square(log(y_true + 1.) - log(y_pred + 1.))`
- *MAPE*  Computes the mean absolute percentage error between y_true & y_pred. `loss = 100 * abs((y_true - y_pred) / y_true)` Note that to avoid dividing by zero, a small epsilon value is added to the denominator.

## Challenging, interesting, or exciting aspects of today's assignment
How to measure model loss with different functions and each one has a different formula.

## Additional resources used 
- [Losses](https://keras.io/api/losses/regression_losses/)
- [MAE](https://medium.com/@polanitzer/the-minimum-mean-absolute-error-mae-challenge-928dc081f031)
- [MSE](https://statisticsbyjim.com/regression/mean-squared-error-mse/)
- [MSLE](https://insideaiml.com/blog/MeanSquared-Logarithmic-Error-Loss-1035)
- [MAPE](https://maheswararedypr.medium.com/mape-mean-absolute-percentage-error-84b3c07028ae)
