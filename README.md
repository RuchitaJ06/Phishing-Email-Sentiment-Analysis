📧 Phishing Email Sentiment Analysis 🛡️
"Decoding Cyber Threats through Linguistic Patterns and Risk Scoring"

🌟 Overview
In the modern digital landscape, phishing remains the #1 entry point for cyberattacks. This project moves beyond simple spam filters by performing a Deep Dive Analysis on over 1,000+ phishing emails.

The core of this project is a Custom Risk-Scoring Engine that identifies threats based on psychological triggers—such as Urgency, Fear, and Authority—to quantify the danger level of incoming communications.

🚀 Key Features & Workflow
1. Advanced Data Cleaning (Python & Regex)
Raw email data is often cluttered with HTML tags and complex encodings. I implemented a cleaning pipeline to:

Strip HTML/CSS noise and metadata.

Decode complex headers (e.g., UTF-8/Base64 patterns).

Normalize text for accurate sentiment and keyword detection.

2. Feature Engineering: The Threat Matrix
I developed a scoring system based on specific "Phishing Pillars":

Urgency Sentiment: Flagging words like Immediate, Urgent, Action Required.

Authority Spoofing: Identifying brand-related keywords (PayPal, Bank, IT Support).

Technical Anomalies: Detecting "Keyword Stuffing" where attackers hide suspicious words in the background to bypass filters.

3. Visual Intelligence (Power BI)
I transformed the processed data into an interactive Threat Intelligence Dashboard to visualize:

Risk Distribution: Categorizing emails into Low, Medium, and High-risk zones.

Top Attacker Domains: Identifying the primary sources of fraudulent emails.

Scatter Plot Analysis: Visualizing the relationship between email length and threat intensity.

📊 Business Insights
The "Critical 8%": My model identified that 8% of the dataset consists of high-urgency threats that require immediate automated blocking.

Psychological Patterns: Attackers most frequently use "Account Security" and "Payment Failure" sentiments to manipulate victims.

Detection Accuracy: By scoring both the Subject and the Body, the model successfully identified outliers with a Risk Score of 100+, which traditional filters often miss.

🛠️ Tech Stack
Language: Python 🐍

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Re (Regular Expressions)

Visualization: Power BI Desktop

Version Control: Git & GitHub

👩‍💻 About the Project
Developed as part of my journey as a Data Analyst, this project demonstrates the power of combining Data Science with Cybersecurity to create proactive defense mechanisms.

How to use this Repo:
Data: The phishing_dashboard_data.csv contains the final processed scores.

Analysis: The Python scripts show the full cleaning and scoring logic.

Visualization: Import the CSV into Power BI to recreate the interactive dashboard.
