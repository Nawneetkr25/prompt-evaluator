# prompt-evaluator
Analyze the effectiveness of AI prompts using user feedback, token counts, and sentiment analysis. A hands-on project in prompt engineering and data science.
# 📊 Prompt Effectiveness Analyzer

A data-driven project that evaluates the effectiveness of various AI prompts based on response quality, user feedback, and key performance metrics like token usage and sentiment.

---

## 🚀 Project Objective

To understand and improve how prompts influence AI-generated responses by:
- Categorizing different types of prompts
- Analyzing response quality using quantitative metrics
- Using user ratings and comments for qualitative analysis
- Identifying patterns in effective prompt design

---

## 📦 Features

- 🧠 Prompt Categorization (Instructional, Coding, Summarization, etc.)
- 📏 Metrics: Response Length, Token Count, Relevance Score
- 💬 Sentiment Analysis of User Comments
- ⭐ User Rating Aggregation
- 📈 Data Visualization via Matplotlib/Seaborn
- 🖥️ (Optional) Streamlit Dashboard

---

## 🗂️ Project Structure

prompt-effectiveness-analyzer/
├── data/ # Prompt, response, and feedback datasets
│ ├── prompts.csv
│ ├── responses.json
│ └── feedback.csv
├── notebooks/ # Jupyter notebooks for data analysis
│ └── analysis.ipynb
├── scripts/ # Python scripts for simulation & analysis
│ ├── collect_responses.py
│ └── analyze_feedback.py
├── README.md
├── requirements.txt
└── LICENSE

yaml
Copy
Edit

📊 Sample Metrics
Average token count per prompt

Sentiment score of user feedback (via TextBlob)

Mean rating per prompt category

Common keywords in high-performing vs. low-performing prompts.

🧪 Technologies Used
Python (pandas, numpy)

Jupyter Notebooks

TextBlob (for NLP)

Matplotlib & Seaborn (visualizations)

OpenAI API (optional) for real responses

Streamlit (optional) for UI dashboard

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request with clear documentation of your changes.

 Acknowledgements
OpenAI for the API and inspiration

Community contributors in prompt engineering and data science.

