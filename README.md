# Basic-statistics-level-1
## Statistical Analysis and Probability Calculations

This repository contains a series of statistical analysis and probability calculation exercises. Each question has been answered with detailed explanations, formulas, and calculations. The exercises cover various topics including data types, probability distributions, expected values, descriptive statistics, skewness, kurtosis, confidence intervals, and hypothesis testing. Additionally, some exercises require the use of Python for more complex calculations.

## Content Overview
Data Types Identification:

## Discrete and continuous data types for various activities.
Nominal, ordinal, interval, and ratio data types for different scenarios.

## Probability Calculations:
Probability of specific outcomes when tossing coins and rolling dice.
Probability of drawing non-blue balls from a set.
Expected number of candies for a randomly selected child based on given probabilities.

## Descriptive Statistics:

Calculation of mean, median, mode, variance, standard deviation, and range for a given dataset.
Comments and inferences based on the calculated statistics.
Expected Value Calculation:
Expected weight of a randomly selected patient from a list.

## Skewness and Kurtosis:

Calculation and interpretation of skewness and kurtosis for given datasets.

## Boxplot and Histogram Analysis:

Drawing inferences from visualizations.
Identifying skewness and calculating the interquartile range (IQR).

## Confidence Intervals:

Calculation of confidence intervals for different confidence levels.
Example involving the average weight of adult males in Mexico.

## Student Marks Analysis:

Calculation of mean, median, variance, and standard deviation.
Interpretation of the student's marks distribution.

## Nature of Skewness:

Identifying skewness based on the relationship between mean and median.

## Kurtosis Interpretation:

Understanding the implications of positive and negative kurtosis.
Probability Calculations for Car MPG:

Probability calculations for specific ranges of MPG values in cars.
Normal Distribution Checks:

Checking normality of datasets such as car MPG and adipose tissue measurements.
Z-Scores and T-Scores:

Calculation of z-scores and t-scores for various confidence intervals.
Hypothesis Testing:

Example of testing a government claim about the average lifespan of light bulbs using t-scores.

## Repository Structure

Q7.csv: Dataset for calculating descriptive statistics.

Q9_a.csv: Dataset for calculating skewness and kurtosis (Car's speed and distance).

Q9_b.csv: Dataset for calculating skewness and kurtosis (SP and Weight).

Cars.csv: Dataset for probability calculations and normal distribution checks (MPG of cars).

wc-at.csv: Dataset for checking normal distribution (Adipose Tissue and Waist Circumference).


# Data Analysis Problems and Solutions

## Q1: Identify the Data Type

**Activity | Data Type**
- Number of beatings from Wife: Discrete Data type
- Results of rolling a dice: Discrete Data type
- Weight of a person: Continuous Data type
- Weight of Gold: Continuous Data type
- Distance between two places: Continuous Data type
- Length of a leaf: Continuous Data type
- Dog's weight: Continuous Data type
- Blue Color: Discrete Data type
- Number of kids: Discrete Data type
- Number of tickets in Indian railways: Discrete Data type
- Number of times married: Discrete Data type
- Gender (Male or Female): Discrete Data type

## Q2: Identify the Data Types

**Data | Data Type**
- Gender: Nominal
- High School Class Ranking: Ordinal
- Celsius Temperature: Interval
- Weight: Ratio
- Hair Color: Nominal
- Socioeconomic Status: Ordinal
- Fahrenheit Temperature: Interval
- Height: Ratio
- Type of living accommodation: Nominal
- Level of Agreement: Ordinal
- IQ (Intelligence Scale): Interval
- Sales Figures: Ratio
- Blood Group: Nominal
- Time Of Day: Interval
- Time on a Clock with Hands: Interval
- Number of Children: Ratio
- Religious Preference: Nominal
- Barometer Pressure: Interval
- SAT Scores: Interval
- Years of Education: Ratio

## Q3: Probability of Two Heads and One Tail in Three Coin Tosses

To find the probability of two heads and one tail, we use the Binomial distribution formula:
\[ P(X=k) = \binom{n}{k} p^k (1-p)^{n-k} \]

The number of ways to get two heads out of three tosses is 3. The probability of getting heads on a single toss is \( \frac{1}{2} \), and the probability of getting tails on a single toss is also \( \frac{1}{2} \).

\[ P(2H, 1T) = 3 \times \left(\frac{1}{2}\right)^2 \times \left(\frac{1}{2}\right) = \frac{3}{8} \]

So, the probability is 37.5%.

## Q4: Probability with Two Dice Rolls

- **Sum equal to 1**: 0
- **Sum less than or equal to 4**: \( \frac{6}{36} = \frac{1}{6} \)
- **Sum divisible by 2 and 3**: \( \frac{6}{36} = \frac{1}{6} \)

## Q5: Probability of Drawing Two Non-Blue Balls

Total ways to draw 2 balls from 7:
\[ \binom{7}{2} = 21 \]

Ways to draw 2 non-blue balls from 5:
\[ \binom{5}{2} = 10 \]

Probability:
\[ \frac{10}{21} \]

## Q6: Expected Number of Candies

\[ E = (1 \times 0.015) + (4 \times 0.20) + (3 \times 0.65) + (5 \times 0.005) + (6 \times 0.01) + (2 \times 0.120) = 3.095 \]

Expected number of candies: 3.095.

## Q7: Descriptive Statistics

**Dataset: Q7.csv**

| Measure         | Points  | Score  | Weight   |
|-----------------|---------|--------|----------|
| Mean            | 3.596563| 3.21725| 17.84875 |
| Median          | 3.695   | 3.325  | 17.71    |
| Mode            | 3.92    | 3.44   | 17.02    |
| Variance        | 0.285881| 0.957379| 3.193166 |
| Standard Deviation| 0.534679| 0.978457| 1.786943 |
| Range           | 2.17    | 3.911  | 8.4      |

**Comments and Inferences:**
1. Points have a relatively low mean and show some variability.
2. Score has a moderate mean and wider range.
3. Weight has less variability compared to Points and Score.

## Q8: Expected Value of Patient's Weight

Given weights:
\[ 108, 110, 123, 134, 135, 145, 167, 187, 199 \]

\[ E(X) = \frac{108 + 110 + 123 + 134 + 135 + 145 + 167 + 187 + 199}{9} = 145.33 \]

Expected Value: 145.33 pounds.

## Q9: Skewness and Kurtosis

**Dataset: Q9_a.csv and Q9_b.csv**

Please refer to the Python notebook for detailed calculations.

## Q10: Inferences from Boxplot and Histogram

- **Histogram**: Right skewed, mean > median, outliers on the higher side.
- **Boxplot**: Outliers on the maximum side.

## Q11: Confidence Intervals for Average Weight

For a sample of 2,000 men:
- **94% CI**: [198.73, 201.26]
- **96% CI**: [198.62, 201.37]
- **98% CI**: [198.43, 201.56]

## Q12: Student Test Scores Analysis

Scores: 34, 36, 36, 38, 38, 39, 39, 40, 40, 41, 41, 41, 41, 42, 42, 45, 49, 56

1. **Mean**: Please refer to the Python notebook.
2. **Median**: Please refer to the Python notebook.
3. **Variance**: Please refer to the Python notebook.
4. **Standard Deviation**: Please refer to the Python notebook.

The data is slightly skewed to the right.

## Q13: Skewness when Mean = Median

No skewness; perfect symmetrical distribution.

## Q14: Skewness when Mean > Median

Right skewness.

## Q15: Skewness when Median > Mean

Left skewness.

## Q16: Positive Kurtosis

Leptokurtic distribution (more peaked).

## Q17: Negative Kurtosis

Platykurtic distribution (flatter and broader).

## Q18: Boxplot Analysis

1. **Distribution**: Positively skewed.
2. **Skewness**: Right skewness.
3. **IQR**: Approximately 8 (Q3 - Q1 = 18 - 10).

## Q19: Comparing Two Boxplots

Both boxplots are normally distributed with no skewness and the same median.

## Q20: Probability Calculations from Cars.csv

1. **P(MPG > 38)**: 0.348
2. **P(MPG < 40)**: 0.729
3. **P(20 < MPG < 50)**: 0.013

## Q21: Normal Distribution Check

- **MPG of Cars**: Follows normal distribution.
- **Adipose Tissue (AT) and Waist Circumference (Waist)**: Do not follow normal distribution.

## Q22: Z-Scores for Confidence Intervals

- **60% CI**: -1.6449
- **94% CI**: -1.8808
- **90% CI**: -0.8416

## Q23: T-Scores for Confidence Intervals with n = 25

- **95% CI**: -2.0639
- **94% CI**: -1.974
- **99% CI**: -2.7969

## Q24: Probability of Average Life of Light Bulbs

Given:
- Population mean = 270 days
- Sample mean = 260 days
- Standard deviation = 90 days
- Sample size = 18

\[ t\_score = \frac{260 - 270}{90 / \sqrt{18}} = -0.471 \]
\[ \text{Probability} = \text{stats.t.cdf}(-0.471, df = 17) = 0.32 \]

Probability: 32%

## Further Analysis

For more detailed calculations and code, please refer to the Python notebook.

# Interview Questions

## Table of Contents
1. [Data Types](#data-types)
2. [Probability](#probability)
3. [Descriptive Statistics](#descriptive-statistics)
4. [Skewness and Kurtosis](#skewness-and-kurtosis)
5. [Confidence Intervals](#confidence-intervals)
6. [Hypothesis Testing](#hypothesis-testing)
7. [Expected Value](#expected-value)
8. [Normal Distribution](#normal-distribution)
9. [Additional Questions](#additional-questions)

### Data Types

1. **Explain the difference between discrete and continuous data.**
   - **Answer:** Discrete data consists of distinct, separate values that can be counted, such as the number of students in a class. Continuous data can take any value within a range and is often measured, like the weight of a person or the temperature.

2. **What are the four scales of measurement in statistics? Provide examples for each.**
   - **Answer:** 
     - **Nominal:** Categories without a specific order (e.g., gender, blood type).
     - **Ordinal:** Categories with a specific order (e.g., high school class ranking).
     - **Interval:** Numeric scales where intervals are meaningful, but there is no true zero (e.g., Celsius temperature).
     - **Ratio:** Numeric scales with a true zero, allowing for meaningful comparisons of magnitude (e.g., weight, height).

### Probability

3. **How do you calculate the probability of a specific outcome when tossing coins or rolling dice?**
   - **Answer:** Probability is calculated by dividing the number of favorable outcomes by the total number of possible outcomes. For example, the probability of getting heads when tossing a coin is 1/2.

4. **What is the Binomial distribution, and when is it used?**
   - **Answer:** The Binomial distribution represents the number of successes in a fixed number of independent Bernoulli trials with the same probability of success. It is used when there are exactly two possible outcomes (success/failure).

### Descriptive Statistics

5. **How do you calculate the mean, median, mode, variance, and standard deviation of a dataset?**
   - **Answer:** 
     - **Mean:** Sum of all values divided by the number of values.
     - **Median:** The middle value when data is ordered.
     - **Mode:** The value that appears most frequently.
     - **Variance:** The average of the squared differences from the mean.
     - **Standard Deviation:** The square root of the variance.

6. **What do the terms "range" and "interquartile range (IQR)" mean, and how are they calculated?**
   - **Answer:** 
     - **Range:** The difference between the maximum and minimum values in a dataset.
     - **IQR:** The difference between the first quartile (Q1) and the third quartile (Q3), representing the middle 50% of the data.

### Skewness and Kurtosis

7. **What is skewness, and how can you identify if data is positively or negatively skewed?**
   - **Answer:** Skewness measures the asymmetry of a data distribution. Data is positively skewed if the tail extends to the right (mean > median), and negatively skewed if the tail extends to the left (median > mean).

8. **What does kurtosis indicate about a dataset? Explain the difference between leptokurtic and platykurtic distributions.**
   - **Answer:** Kurtosis measures the "tailedness" of the data distribution. Leptokurtic distributions have positive kurtosis, with fatter tails and a sharper peak. Platykurtic distributions have negative kurtosis, with thinner tails and a flatter peak.

### Confidence Intervals

9. **How do you calculate a confidence interval, and what does it represent?**
   - **Answer:** A confidence interval is calculated using the sample mean, sample standard deviation, and the critical value from the z or t distribution. It represents a range of values within which the population parameter is likely to fall.

10. **Given a sample mean and standard deviation, how would you construct a 95% confidence interval?**
    - **Answer:** The formula is: \(\text{CI} = \bar{x} \pm z \left(\frac{s}{\sqrt{n}}\right)\), where \(\bar{x}\) is the sample mean, \(z\) is the z-value for 95% confidence, \(s\) is the sample standard deviation, and \(n\) is the sample size.

### Hypothesis Testing

11. **Explain the concept of hypothesis testing. What are null and alternative hypotheses?**
    - **Answer:** Hypothesis testing is a method to determine if there is enough evidence to reject a null hypothesis (H0) in favor of an alternative hypothesis (H1). The null hypothesis represents no effect or no difference, while the alternative hypothesis represents the effect or difference being tested.

12. **How do you calculate a t-score and z-score, and when would you use each?**
    - **Answer:** 
      - **Z-score:** \( z = \frac{x - \mu}{\sigma} \), used when population variance is known and sample size is large.
      - **T-score:** \( t = \frac{x - \mu}{s/\sqrt{n}} \), used when population variance is unknown and sample size is small.

### Expected Value

13. **What is the expected value, and how is it calculated in probability and statistics?**
    - **Answer:** The expected value is the weighted average of all possible values of a random variable, calculated as \(E(X) = \sum [x_i \cdot P(x_i)]\).

14. **Provide an example where calculating the expected value is useful in real-world scenarios.**
    - **Answer:** Calculating expected value is useful in financial decision-making, such as determining the expected return on an investment by considering all possible outcomes and their probabilities.

### Normal Distribution

15. **What are the properties of a normal distribution?**
    - **Answer:** A normal distribution is symmetric, bell-shaped, and characterized by its mean and standard deviation. Approximately 68% of data falls within one standard deviation, 95% within two, and 99.7% within three.

16. **How do you check if a dataset follows a normal distribution?**
    - **Answer:** You can use graphical methods like histograms, Q-Q plots, or statistical tests like the Shapiro-Wilk test to check for normality.

### Additional Questions

17. **Describe how you would interpret a boxplot. What do the different components represent?**
    - **Answer:** A boxplot displays the distribution of data through its quartiles. The box represents the IQR, the line inside the box is the median, and the "whiskers" extend to the minimum and maximum values within 1.5 times the IQR. Outliers are plotted as individual points.

18. **Explain the steps to perform a hypothesis test for the mean lifespan of a product based on sample data.**
    - **Answer:** 
      1. State the null and alternative hypotheses.
      2. Choose a significance level (\(\alpha\)).
      3. Calculate the test statistic (z or t-score).
      4. Determine the p-value or critical value.
      5. Compare the p-value with \(\alpha\) or the test statistic with the critical value.
      6. Draw a conclusion: reject or fail to reject the null hypothesis.

19. **How would you calculate the probability of an event using the normal distribution?**
    - **Answer:** Convert the event value to a z-score using \( z = \frac{x - \mu}{\sigma} \), then use the standard normal distribution table or a calculator to find the corresponding probability.

20. **What insights can you derive from analyzing skewness and kurtosis of a dataset?**
    - **Answer:** Skewness provides information on the symmetry of the data distribution, while kurtosis indicates the "tailedness." Together, they help understand the shape and spread of the data, identifying potential outliers and the nature of the distribution.
