# SpringBoard Exercise: Human body temperature (Exploratory Data Analysis)

## Context
This repository contains an exercise on Exploratory Data Analysis for the SpringBoard program. The data set used is the mean normal body temperature first conceptualized and reported by Carl Wunderlich in a famous 1868 book. This reported that the mean normal body temperature was 37 ∘C or 98.6 ∘F.

This exercise, analyses the dataset of human body temperatures and employs the concepts of hypothesis testing, confidence intervals, and statistical significance.

The following questions and the working to obtain their answers below can be found in the jupyter notebook.

1. Is the distribution of body temperatures normal?
  - A: Yes body temperatures are normally distributed

2. Is the sample size large? Are the observations independent?
  - A: Yes the sample size is large (>30)
  - A: Yes the observations appear to be independent

3. Is the true population mean really 98.6 degrees F?
  - A: No the true population mean appears to be lower than 98.6 degrees F
  - This was done using a one-sample test using a z  statistic due to the large sample size.

4. Draw a small sample of size 10 from the data and repeat both tests.
  - A: The true population mean still appears to be lower than 98.6 degrees F
  - This was done using a one-sample test using a t  statistic due to the small sample size.

5. At what temperature should we consider someone's temperature to be "abnormal"?
  - 99.5% confidence interval has a z-score of ±2.81 this translates to a max temperature of  96.2  to  100.3 F

6. Is there a significant difference between males and females in normal temperature?
  - The low p value suggests that females have a statistically significantly higher body temperature than males.

Summary: The human body temperature appears to be lower at approximately 98.3 F on average. However, females have a significantly higher average body temperatures 98.4 F vs their male counterparts who average 98.1 F. The analysis, is statistically confident in rejecting the hypothesis that the true population mean temperature is 98.6 ∘F.
