# 🧪 Experiment No. 14: Data Normalization and Data Types

## Name: Bhavya Pandya
## PRN: 25070123139
## Branch: F.Y. E&TC (2025–29)
## Batch: A1
## Subject: Exploratory Data Analysis with Python

### 1. Aim

The aim of this experiment is to study and implement various data normalization techniques and understand different data types, along with converting categorical data into numerical form for effective data analysis.

### 2. Objective
To understand the concept and importance of data normalization
To apply normalization techniques such as Min-Max, Z-Score, and Decimal Scaling
To understand different types of data (numerical and categorical)
To convert categorical data into numerical format using encoding techniques
To prepare datasets suitable for machine learning and data analysis
3. Concepts Used
3.1 Data Normalization

Data normalization is the process of scaling numerical values into a specific range so that all features contribute equally during analysis.

### 3.2 Types of Normalization
Min-Max Normalization
Z-Score Normalization
Decimal Scaling
3.3 Data Types
Numerical Data (Continuous and Discrete)
Categorical Data
3.4 Encoding Techniques
Label Encoding
One-Hot Encoding
Dummy Encoding
4. Theory
4.1 Introduction to Data Normalization

In real-world datasets, values often vary significantly in scale. For instance, salary values may be in thousands, while ratings may be between 0 and 5. Such differences can negatively affect data analysis and machine learning algorithms.

Data normalization helps in bringing all values to a common scale without altering their relative relationships.

### 4.2 Need for Normalization
Ensures fair comparison between variables
Prevents bias caused by large values
Improves performance of machine learning algorithms
Helps in faster convergence during model training
4.3 Types of Normalization Techniques (With Formulas)
1. Min-Max Normalization

This technique rescales data into a fixed range, usually between 0 and 1.

𝑋
′
=
𝑋
−
𝑋
𝑚
𝑖
𝑛
𝑋
𝑚
𝑎
𝑥
−
𝑋
𝑚
𝑖
𝑛
X
′
=
X
max
	​

−X
min
	​

X−X
min
	​

	​


Where:

X = Original value
Xₘᵢₙ = Minimum value
Xₘₐₓ = Maximum value
X' = Normalized value
2. Z-Score Normalization (Standardization)

This method standardizes data based on mean and standard deviation.

𝑍
=
𝑋
−
𝜇
𝜎
Z=
σ
X−μ
	​

𝑥
x
𝜇
μ
𝜎
σ
𝑧
=
𝑥
−
𝜇
𝜎
≈
1.2
z=
σ
x−μ
	​

≈1.2
Φ
(
𝑧
)
≈
88.5
%
Φ(z)≈88.5%

Where:

X = Original value
μ = Mean of data
σ = Standard deviation
Z = Standardized value
3. Decimal Scaling Normalization

This technique scales values by dividing them by powers of 10.

𝑋
′
=
𝑋
10
𝑗
X
′
=
10
j
X
	​


Where:

X = Original value
j = Number of digits in the maximum value
X' = Normalized value
4.4 Data Types
1. Numerical Data
Represents measurable quantities
Continuous: Height, weight, temperature
Discrete: Number of students, count values
2. Categorical Data
Represents labels or categories
Cannot be directly used in mathematical operations
Example: Gender, Color, City
4.5 Encoding of Categorical Data
1. Label Encoding

Assigns numerical values to categories.
Example: Male = 0, Female = 1

2. One-Hot Encoding

Creates separate columns for each category using binary values (0 or 1).

3. Dummy Encoding

Similar to one-hot encoding but removes one column to avoid redundancy.

### 4.6 Importance of Normalization and Encoding
Makes data suitable for machine learning models
Improves accuracy and efficiency
Ensures consistency across dataset
Enables fair comparison of features
Reduces computational complexity
📊 Visualization of Normalization Concepts
9
### 5. Conclusion

In this experiment, various normalization techniques such as Min-Max, Z-Score, and Decimal Scaling were studied and implemented. These methods helped in scaling numerical data effectively and improving consistency across features.

Additionally, categorical data was converted into numerical form using encoding techniques, making it suitable for analysis and machine learning applications.

Overall, this experiment highlights the importance of data preprocessing in exploratory data analysis and demonstrates how normalization and encoding improve data quality, performance, and interpretability.
