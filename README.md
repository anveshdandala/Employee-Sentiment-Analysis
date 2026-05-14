# Employee Sentiment Analysis

## Project Overview

This project analyzes employee email communication using NLP-based sentiment analysis and machine learning techniques. The workflow includes sentiment classification, exploratory data analysis (EDA), employee scoring, employee ranking, flight-risk detection, and predictive modeling.

The sentiment analysis model classified employee emails into:
- Positive
- Neutral
- Negative

Sentiment scores were then aggregated monthly to identify communication trends and employee engagement patterns.

---

# Top Positive Employees

The top positive employees were identified using aggregated monthly sentiment scores.

| Employee | Score |
|---|---|
|johnny.palmer@enron.com | 50 |
|bobette.riner@ipgdirect.com | 42 |
|sally.beck@enron.com | 42 |

---

# Top Negative Employees

The top negative employees were identified using the lowest monthly sentiment scores.


| Employee| Score |
|---|---|
| kayne.coulter@enron.com | 16 |
|john.arnold@enron.com | 17 |
|rhonda.denton@enron.com | 18 |


---

# Flight Risk Employees

Employees were flagged as potential flight risks if they sent multiple negative emails within a rolling 30-day period.

Flagged Employees:

- john.arnold@enron.com
- patti.thompson@enron.com
- sally.beck@enron.com
---

# Key Insights

- Most employee emails were classified as neutral, which is expected in workplace communication datasets.
- Positive and negative emails formed a smaller percentage of overall communication.
- Employee communication trends varied across months.
- Some employees consistently displayed stronger negative communication patterns.
- Message frequency and message length alone were not strong predictors of sentiment trends in the regression model.

---

# Recommendations

- Employees with repeated negative communication patterns should be monitored for possible disengagement or workplace concerns.
- Additional contextual analysis could improve sentiment interpretation accuracy.
- Future analysis could include topic modeling, advanced NLP techniques, or behavioral trend forecasting.
- Combining communication sentiment with organizational metrics may improve predictive performance.

---

# Files Included

- `test_with_sentiment.xlsx`
- `monthly_employee_scores.xlsx`
- `employee_rankings.xlsx`
- `flight_risk_employees.xlsx`
- `Employee_Sentiment_Report.docx`
- `visualization/`
