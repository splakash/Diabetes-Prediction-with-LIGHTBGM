# Diabetes-Prediction-with-LIGHTBGM
checking the accuracies of machine learning classification algorithms on diabetes dataset

 In this model Detecting Outliers Using Standard Deviation
When the data, or certain features in the dataset, follow a normal distribution, you can use the standard deviation of the data, or the equivalent z-score to detect outliers.
For data that is normally distributed, around 68.2% of the data will lie within one standard deviation from the mean. Close to 95.4% and 99.7% of the data lie within two and three standard deviations from the mean, respectively.

Let’s denote the standard deviation of the distribution by σ, and the mean by μ.

One approach to outlier detection is to set the lower limit to three standard deviations below the mean (μ - 3*σ), and the upper limit to three standard deviations above the mean (μ + 3*σ). Any data point that falls outside this range is detected as an outlier.

**#For the standardization we used robust scaler**
Standardizing is a popular scaling technique that subtracts the mean from values and divides by the standard deviation, transforming the probability distribution for an input variable to a standard Gaussian (zero mean and unit variance). Standardization can become skewed or biased if the input variable contains outlier values.

Robust Scaler Transforms
The robust scaler transform is available in the scikit-learn Python machine learning library via the RobustScaler class.


Interestingly, the definition of the scaling range can be specified via the “quantile_range” argument. It takes a tuple of two integers between 0 and 100 and defaults to the percentile values of the IQR, specifically (25, 75). Changing this will change the definition of outliers and the scope of the scaling.
