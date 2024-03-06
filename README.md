The machine learning consists of four paradigms as supervised learning, unsupervised learning, reinforcement learning and semi-supervised learning.
The programs necessary for the basic introduction of machine learning models by supervised learning and unsupervised learning is provided. 
Firstly, we load the dataset. The dataset used here is in .csv(comma separeted values) format. Then we perform the data preprocessing which includes the following process:

Data Cleaning: This step involves handling missing data, outliers, and noise in the dataset. Common techniques include imputation for missing values, removing outliers, and smoothing noisy data.

Data Transformation: Data transformation involves converting the dataset into a format suitable for analysis. This can include scaling features to a similar range (e.g., normalization or standardization), encoding categorical variables into numerical format (e.g., one-hot encoding or label encoding), and handling skewed distributions (e.g., log transformation).

Feature Selection/Extraction: In this step, relevant features are selected or extracted from the dataset to reduce dimensionality and improve model performance. Techniques include correlation analysis, feature importance ranking, principal component analysis (PCA), and other dimensionality reduction methods.

Splitting the Dataset: The dataset is typically split into training, validation, and test sets. The training set is used to train the model, the validation set is used to tune hyperparameters and evaluate model performance during training, and the test set is used to evaluate the final model's performance.

Feature Scaling: Feature scaling ensures that all features have a similar scale, preventing features with large magnitudes from dominating those with smaller magnitudes. Common scaling techniques include normalization (scaling features to a range of [0, 1]) and standardization (scaling features to have a mean of 0 and a standard deviation of 1).

Dimensionality Reduction: In cases where the dataset has a large number of features, dimensionality reduction techniques such as PCA (Principal Component Analysis) or LDA (Linear Discriminant Analysis) can be applied to reduce the number of features while preserving most of the dataset's variance.

