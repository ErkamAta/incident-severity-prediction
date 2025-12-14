🚨 Incident Severity Prediction for Enterprise IT Operations
📌 Problem

Enterprise IT environments generate thousands of incidents daily.
However, not every alert deserves the same level of attention.

This leads to:

Alert fatigue

Delayed response to critical incidents

Inefficient use of IT resources

🎯 Objective

Build a lightweight machine learning system that:

Automatically classifies IT incidents as Low / Medium / Critical

Prioritizes incidents based on business impact

Maximizes Critical incident recall

🧠 Approach

Domain-driven synthetic dataset

Simulated real-world IT/ERP incidents

Sources: Database, Application, Network, Authentication, Infrastructure

Systems: ERP, Finance, CRM, HR, Warehouse, Reporting

Rule-based severity labeling

Business impact–oriented rules

Factors:

Affected users

Resolution time

System criticality

Historical frequency

Baseline ML model

Logistic Regression

One-hot encoding for categorical features

Class imbalance handled via class weighting

📊 Results

Critical Recall: 0.90

Model focuses on minimizing missed critical incidents

Medium / Low misclassifications tolerated by design

This aligns with real-world IT operations where missing a critical incident is far more costly than over-alerting.

🧩 Key Learnings

Label design is more important than model complexity

Domain knowledge significantly improves ML outcomes

Simple models can deliver strong business value

🔜 Future Improvements

Time-based features (business hours, weekdays)

RandomForest / Gradient Boosting comparison

Real-time scoring integration

🛠️ Tech Stack

Python

pandas

scikit-learn
