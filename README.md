CREDITWISE: A MACHINE LEARNING TOOL FOR LOAN RISK CLASSIFICATION
A School Project Report
CHAPTER ONE: INTRODUCTION
1.1 Background

Banks routinely assess the creditworthiness of loan applicants to minimize default risk. Traditional approaches rely on manual review or static scoring rules, which can be slow, inconsistent, and prone to subjective bias. With growing interest in artificial intelligence, machine learning (ML) offers a data-driven alternative to automate preliminary credit screening.

This project leverages the publicly available German Credit Dataset to build a simple but effective ML system that classifies applicants as “Good” or “Bad” credit risks, supporting relationship managers in faster and more informed decision-making.

1.2 Problem Statement

Loan defaults cause major financial losses, and in many institutions—especially in developing regions—the assessment process remains manual, leading to:

Inconsistent decision-making

Missed patterns that ML models could detect

Delays that negatively affect customer experience

Existing commercial scoring systems are expensive, proprietary, or opaque. A transparent, educational, and accessible ML-powered prototype is needed to demonstrate how automation can support (not replace) human judgment.

1.3 Research Questions

Can machine learning accurately classify credit risk using the German Credit Dataset?

Which algorithm—Logistic Regression or Random Forest—balances accuracy and interpretability best?

How can predictions be explained clearly to non-technical banking staff?

1.4 Objectives
General Objective

To design and implement a machine learning–based loan risk classification system for relationship managers using open-source tools.

Specific Objectives

Preprocess and analyze the German Credit Dataset using supervised learning methods.

Build a user-friendly web interface for real-time predictions.

Provide transparent explanations highlighting key risk factors.

1.5 Justification

This project demonstrates responsible AI use in education by using open data, open tools, and interpretable models. It promotes digital literacy in finance while showing students how ML workflows—data preprocessing, model selection, and explainability—translate into a practical system.

1.6 Scope

Dataset: German Credit (1,000 applicants, 20 features)

Models: Logistic Regression and Random Forest

Interface: Streamlit web application

Outputs: Risk class (“Good”/“Bad”), confidence score, top 3 explanatory factors

Deployment: Local machine or Streamlit Cloud

