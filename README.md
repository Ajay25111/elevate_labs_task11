📊 A/B Testing — Hypothesis Testing in Python
📌 Project Overview

This project demonstrates how to perform A/B testing using Python to make data-driven product and marketing decisions.
We analyze an e-commerce marketing dataset to evaluate whether showing advertisements leads to a statistically significant increase in user conversions compared to a control group.

The analysis follows a complete A/B testing workflow, including hypothesis formulation, statistical testing, confidence interval estimation, visualization, and business recommendations.

🎯 Objective

Compare conversion rates between control and test groups

Apply hypothesis testing using statistical methods

Determine whether ads have a real impact on conversions

Provide a business recommendation based on data

🧰 Tools & Technologies

Platform: Google Colab

Language: Python

Libraries:

pandas – data manipulation

numpy – numerical operations

scipy – statistical tests

matplotlib – visualization

📁 Dataset Description

The dataset contains user-level marketing and conversion data.

Key Columns Used
Column Name	Description
user id	Unique identifier for each user
test group	Group assignment (psa = control, ad = test)
converted	Conversion outcome (1 = converted, 0 = not converted)
total ads	Number of ads shown to the user
most ads day	Day with highest ad exposure
most ads hour	Hour with highest ad exposure

Note:
psa represents the control group (no real ads), and ad represents the test group (ads shown).

🧪 Experiment Design
Hypotheses

Null Hypothesis (H₀):
There is no difference in conversion rates between the control and test groups.

Alternative Hypothesis (H₁):
There is a significant difference in conversion rates between the two groups.

Significance Level

α (alpha) = 0.05

📐 Methodology

Load and clean the dataset

Identify control (psa) and test (ad) groups

Calculate conversion rates for each group

Perform an independent t-test

Compute 95% confidence interval for the difference in conversion rates

Visualize conversion rate comparison

Interpret statistical results

Provide final business recommendation

📊 Key Results
Conversion Rate Difference

Mean Difference: 0.00769

95% Confidence Interval: (0.00595, 0.00943)

Interpretation

The confidence interval does not include zero

This indicates a statistically significant improvement

Users exposed to ads converted ~0.77% more than control users

📈 Visualization

A bar chart was used to compare conversion rates between the control and ad groups, making the results easy to interpret visually.

🧠 Business Insight

Even a 0.77% increase in conversion rate can lead to a large revenue impact when applied to thousands or millions of users.
The data strongly suggests that advertisements positively influence user conversion behavior.

✅ Final Recommendation

Based on the statistical evidence, the advertisement campaign should be rolled out to all users, as it leads to a significant increase in conversion rates.

📦 Project Deliverables

task11_abtest.ipynb – Jupyter notebook with full analysis

ab_test_summary.csv – Conversion rate summary

final_recommendation.txt – Business recommendation

README.md – Project documentation

🚀 How to Run the Project

Open the notebook in Google Colab

Upload the dataset to /content/

Run cells sequentially

Review outputs and generated files

🏁 Conclusion

This project demonstrates a complete A/B testing pipeline and highlights how statistical analysis can support data-driven decision making in real-world business scenarios.

👤 Author

Ajay
Aspiring Data Analyst | Python | Statistics | Machine Learning
