# 🔍 AI-Powered Research Bot

An AI-driven research assistant that automates the process of gathering and summarizing research papers and web articles. Built using Streamlit and powered by Gemini AI, ArxivTools, and DuckDuckGoTools.

## 🛠️ Features

✅ Fetches academic research papers from Arxiv

✅ Retrieves relevant web articles using DuckDuckGo search

✅ Generates structured research reports with citations and references

✅ Outputs the report in Markdown format with clickable links

✅ Provides a downloadable PDF version of the report

✅ Streamlit-based interactive UI

## 📂 Project Structure

```bash
ai-powered-research-bot/
├── app.py                 # Main Streamlit application
├── .env                   # API key storage (not to be committed)
├── requirements.txt       # List of dependencies
├── README.md              # Documentation
└── .gitignore             # Ignore unnecessary files
```

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MVenkatsai02/Reportgenerator
cd ai-powered-research-bot
```

### 2️⃣ Set Up a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 🖥️ Running Locally

### 🔹 Start Streamlit Application

```bash
streamlit run app.py
```

Your UI will be available at:

👉 http://localhost:8501

## 🌍 Deployment

### 4️⃣ Deploy on Streamlit Cloud

Push the project to GitHub.
Go to Streamlit Cloud → Click "Deploy an App".
Select GitHub repo → Set main file path to `app.py`.
Deploy and share your app link.

## 📌 Example Usage

1️⃣ Open the Streamlit UI.

2️⃣ Enter your Gemini API Key.

3️⃣ Provide a research topic.

4️⃣ Click **Generate Research Report**.

5️⃣ Download the generated report as a PDF.

## 🔧 Troubleshooting

💡 **Issue: API Key Not Found**
✔️ Ensure `.env` file contains `GOOGLE_API_KEY=your_api_key_here`.
✔️ Restart the Streamlit app after updating the `.env` file.

💡 **Issue: Missing Dependencies**
✔️ Run `pip install -r requirements.txt`.
✔️ Ensure virtual environment is activated.

## 🛡️ License

This project is open-source under the MIT License.

## 📩 Contact & Contributions

🔹 Feel free to fork this repo & contribute!

🔹 Found a bug? Create an issue on GitHub.

🔹 Questions? Reach out via email: venkatsaimacha123@gmail.com

🚀 Built with ❤️ using Streamlit & Gemini AI 🚀

