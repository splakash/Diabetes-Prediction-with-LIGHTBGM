# Diabetes-Prediction-with-LIGHTBGM
checking the accuracies of machine learning classification algorithms on diabetes dataset

 In this model Detecting Outliers Using Standard Deviation
When the data, or certain features in the dataset, follow a normal distribution, you can use the standard deviation of the data, or the equivalent z-score to detect outliers.
For data that is normally distributed, around 68.2% of the data will lie within one standard deviation from the mean. Close to 95.4% and 99.7% of the data lie within two and three standard deviations from the mean, respectively.

Let’s denote the standard deviation of the distribution by σ, and the mean by μ.

One approach to outlier detection is to set the lower limit to three standard deviations below the mean (μ - 3*σ), and the upper limit to three standard deviations above the mean (μ + 3*σ). Any data point that falls outside this range is detected as an outlier.

