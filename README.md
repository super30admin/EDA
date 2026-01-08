Exploratory Data Analysis (EDA) — FAANG-Style Labs

This repository contains two structured EDA labs designed to teach how ML engineers at FAANG explore real data, not just how to plot charts.

The focus is on:

Asking the right questions

Detecting data issues early

Building intuition before modeling

Communicating insights clearly

🧠 Why This Repository Exists

In real ML systems:

Most failures come from bad data understanding, not bad models.

These labs train you to:

Think like a production ML engineer

Avoid misleading conclusions

Prepare clean, trustworthy inputs for ML models

📁 Repository Structure
EDA/
├── eda_titanic_matplotlib.ipynb
├── eda_adult_income_seaborn.ipynb
└── README.md

🧪 Lab 1 — Titanic EDA (Matplotlib-First)

Notebook: eda_titanic_matplotlib.ipynb

Dataset

Titanic survival dataset

Mixed numerical + categorical features

Small but rich in patterns

Focus Areas

Univariate analysis (distributions)

Bivariate analysis (survival vs features)

Handling missing values

Detecting misleading correlations

Using Matplotlib only (low-level control)

Skills Practiced

Asking hypothesis-driven questions

Choosing the right plot type

Avoiding over-plotting

Explaining insights verbally (interview-ready)

🧪 Lab 2 — Adult Income EDA (Seaborn-First)

Notebook: eda_adult_income_seaborn.ipynb

Dataset

Adult Income (UCI)

Large, noisy, real-world data

Strong bias & imbalance signals

Focus Areas

Multivariate analysis

Categorical vs numerical relationships

Distribution shifts

Detecting bias and leakage risks

Using Seaborn for statistical visualization

Skills Practiced

High-level statistical plotting

Feature interaction reasoning

Bias detection (gender, education, hours worked)

Communicating uncertainty

🔍 What You Should Learn From These Labs

By completing both notebooks, you should be able to:

✅ Explain why a plot is chosen
✅ Detect missing data patterns early
✅ Identify misleading correlations
✅ Reason about feature usefulness before modeling
✅ Communicate insights clearly to non-technical stakeholders

🚫 What This Repository Is NOT

❌ Not a plotting tutorial

❌ Not about “pretty graphs”

❌ Not model training

EDA happens before ML — and decides whether ML succeeds.

🧠 FAANG Interview Alignment

These labs directly prepare you for:

“Walk me through how you’d explore this dataset”

“What issues do you see before modeling?”

“How would this data break a model in production?”

“Which features would you drop and why?”

▶️ How to Run
Option 1: Google Colab

Open any notebook

Click Open in Colab

Run cells top-to-bottom

Option 2: Local
pip install numpy pandas matplotlib seaborn
jupyter notebook

🧪 Suggested Extensions (Optional)

Add feature importance reasoning (no modeling)

Compare distributions before/after cleaning

Detect Simpson’s paradox

Write EDA conclusions as a 1-page report

🎯 Final Takeaway

Great ML starts with great EDA.

If you can explain your EDA clearly,
you’re already thinking like a FAANG ML engineer.
