# Assignment 2 (Data Science Laboratory)

### Problem Statement


1. **Merge the Data (Class-wise):** Combine two classes or activities from the Assignment 1 dataset into a single dataset, based on class labels.
2. **Convert to Frequency Domain (FFT):**
   Apply the Fast Fourier Transform (FFT) to your time-domain dataset to convert it to the frequency domain. Then, create a stem plot to visualize the frequency components.Your data from the time domain, where signals vary over time, to the frequency domain, where signals are represented by their frequency components. This process reveals the dominant frequencies and their amplitudes within the data, providing insights into periodic patterns or signals that may not be visible in the time domain. The resulting frequency-domain data can be analyzed or visualized to understand the
   underlying spectral characteristics of the dataset.
3. **Outlier Removal (Column-wise):** Identify and remove outliers from the merged time-domain dataset by analyzing each column individually. To identify and remove outliers from a merged time-domain dataset, begin by analyzing each column individually, as outliers are data points that significantly deviate from the majority, potentially distorting the analysis and leading to misleading conclusions. The process starts with statistical analysis, where key metrics such as the mean, standard deviation, and interquartile range (IQR) are calculated for each column. These metrics help establish thresholds for identifying outliers. For example, any data point more than three standard deviations from the mean or beyond 1.5 times the IQR above the third quartile or below the first quartile can be flagged as an outlier.

**After  calculating these statistics, visualize the data using box plots or scatter plots to detect anomalies that might not be evident through numerical analysis alone. Visualization aids in confirming the presence of outliers by highlighting points that fall outside the expected range.  Once outliers are identified, decide on the best approach for handling them. You can either remove the outliers from the dataset or replace them with more representative values, such as the median of the column. Finally, reanalyze the dataset after outlier removal to ensure that the remaining data accurately reflects the underlying trends, leading to more reliable and meaningful results.**

4. **Feature Extraction:** Extract two features from the dataset: one characteristic from the time-domain data and another from the frequency-domain data.
5. **Principal Component Analysis (PCA):** Perform PCA on your input data to analyze its variance and reduce dimensionality, focusing on the most significant components. Principal Component Analysis (PCA) is a statistical method used for reducing the dimensionality of large datasets while retaining most of the original data's variability. It works by identifying the principal components—orthogonal directions that capture the maximum variance in the data. By projecting the data onto these components, PCA reduces the number of variables, simplifying the dataset while preserving its essential patterns. The first principal component captures the most variance, followed by subsequent components. PCA is widely used for data  compression, noise reduction, and feature extraction, making complex datasets easier to analyze and interpret.

**Some Useful Links:**

**DFT:**[ **https://medium.com/sho-jp/fourier-transform-101-part-4-discrete-fourier-transform-8fc3fbb763f3**](https://medium.com/sho-jp/fourier-transform-101-part-4-discrete-fourier-transform-8fc3fbb763f3)

**FFT**:[https://builtin.com/articles/fast-fourier-transform](https://builtin.com/articles/fast-fourier-transform)

[https://medium.com/analytics-vidhya/simplifying-audio-data-fft-stft-mfcc-for-machine-learning-and-deep-learning-443a2f962e0e](https://medium.com/analytics-vidhya/simplifying-audio-data-fft-stft-mfcc-for-machine-learning-and-deep-learning-443a2f962e0e)
