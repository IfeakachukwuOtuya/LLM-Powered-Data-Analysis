# 📊 LLM-Powered Data Analysis Tool

An intelligent Streamlit web app that turns your CSV data into a **conversational data analyst** using **OpenAI’s GPT models**.

Upload a CSV → Ask questions in plain English → Get instant insights, visualizations, and summaries.

---

## 🚀 Features

- 💬 **Natural Language Queries** – Ask questions like *"Show sales trends by month"* or *"Plot a correlation heatmap"*
- 🤖 **AI-Powered Analysis** – Uses OpenAI’s GPT models to generate and execute Python code for analysis
- 📈 **Smart Visualizations** – Automatically produces charts and summaries using `pandas`, `matplotlib`, and `seaborn`
- 🧠 **Prompt Optimization** – Summarizes data for token efficiency and accuracy
- 🔒 **Privacy First** – Everything runs privately in your session
- 💾 **Report Export** – Download a full HTML report of your analysis

---

## 🧰 Tech Stack

- [Streamlit](https://streamlit.io/) – UI framework
- [OpenAI API](https://platform.openai.com/) – LLM for natural language data analysis
- [pandas](https://pandas.pydata.org/) – Data manipulation
- [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/) – Data visualization
- Python 3.9+

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone <https://github.com/IfeakachukwuOtuya/LLM-Powered-Data-Analysis>
cd llm-powered-data-analysis
pip install -r requirements.txt
Create a .streamlit folder and secret.toml file in i,  in the project root:
