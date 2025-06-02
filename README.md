# 📄 PDF Reader Q&A with Gemini

This is a simple Streamlit web app that lets you **upload PDF files and ask questions** based on their content. It uses **Google Gemini** (via LangChain) to generate intelligent answers from the PDF content.

---

## 🔧 How It Works

1. Upload one or more PDF files.
2. The app reads and processes the text.
3. Ask any question related to the PDF content.
4. Get context-aware answers powered by Google Gemini.

---

## 🚀 Getting Started

### 1. Clone the Repository

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Set Up Your API Key
```ini
GOOGLE_API_KEY=your_google_api_key_here
```
### 4. Run the App
```terminal
streamlit run main.py
```

## 🛠 Tech Used

- Streamlit

- PyPDF2

- LangChain

- Google Gemini

- FAISS
