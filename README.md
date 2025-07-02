# Cereal Packet Weight Analysis 🥣📊

This project investigates whether cereal packets meet the minimum claimed net weight of 450 grams using basic statistical techniques.

## 📌 Objective

To assess if there is statistical evidence that the cereal packets are underfilled using hypothesis testing, and to check the distribution and data integrity using visual tools like boxplots and Q-Q plots.

## 📂 Dataset

A sample of 7 cereal packet weights (in grams):

```
445, 453, 447, 451, 440, 460, 449
```

## 🔍 Statistical Methods Used

* **Boxplot Construction**: To check for unusual values and spread.
* **Q-Q Plot**: To assess whether the data follows a normal distribution.
* **Hypothesis Testing (One-sample t-test)**:

  * Null Hypothesis (H₀): μ = 450
  * Alternative Hypothesis (H₁): μ < 450
  * Significance Level: 0.05
* **Interpretation of Statistical Results**

## 📊 Tools

* R programming language
* Base R plotting functions (`qqnorm`, `qqline`, `boxplot`)
* `t.test()` for hypothesis testing


## 🧠 Key Insights

* The boxplot revealed no outliers in the sample.
* The Q-Q plot suggested that the data could be approximated by a normal distribution.
* Based on the t-test, there was **no significant evidence at the 5% level** to conclude the cereal packets are underfilled.

