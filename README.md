# [Live link](https://ai-research-summarizer.streamlit.app/)

# 📄 AI-Powered Research Summarizer

Welcome to the **AI-Powered Research Summarizer**, a Streamlit-based web app powered by Google’s Gemini 1.5 Pro via LangChain. It generates clear, structured, and audience-tailored summaries of research papers—perfect for students, researchers, developers, or professionals needing quick insights into academic content.

---

## 🚀 Features

- 📘 **Supports Paper Types**:
  - Research Article
  - Review Paper
  - Technical Report
  - Thesis
  - Whitepaper
  - Conference Paper

- 🧠 **Multiple Summary Styles**:
  - Beginner Friendly
  - Technical
  - Code Oriented
  - Mathematical
  - Academic

- 📏 **Flexible Summary Lengths**:
  - Short (1–2 paragraphs)
  - Medium (3–5 paragraphs)
  - Long (Detailed subpoints)
  - Extended (Section-wise breakdown)
  - Comprehensive (Full breakdown with math & examples)

- 🌍 **Multilingual Support**:
  - English, Hindi, Spanish, French, German, Chinese, Arabic, Portuguese, Russian, Japanese

- 📤 **Upload & Parse PDFs**:
  - Extracts content from `.pdf` research papers via PyMuPDF

- 📝 **Text Input Option**:
  - Paste abstract or full content directly

- 🎧 **Text-to-Speech Playback**:
  - Listen to the summary using gTTS
  - Audio playback directly in the browser

- 📄 **Export Options**:
  - Download summary as **DOCX**
  - Export as **PDF** (formatted)

- ✨ **Dynamic Prompt Engineering**:
  - Context-aware generation using LangChain’s `PromptTemplate`

---

## ⚙️ Tech Stack

- 🧠 `langchain-google-genai` (Gemini 1.5 Pro)
- 🌐 `langchain`, `langchain-core`
- 💻 `streamlit` for UI
- 📄 `pymupdf` for PDF parsing
- 📝 `python-docx`, `reportlab` for exporting summaries
- 🎙️ `gTTS` for audio summaries
- 🔐 `python-dotenv` for secure API key handling

---

## 📦 Installation

### 1. Clone the repository

```bash
https://github.com/vikas-kashyap97/ai-research-summarizer.git
cd ai-research-summarizer
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install the required packages

```bash
pip install -r requirements.txt
```
### 4. Add your Google Generative AI API key

```bash
GOOGLE_API_KEY=your-google-api-key-here
```
### 5. Run the application

```bash
streamlit run prompt_ui.py
```

## On the UI:

- Choose the type of research document.

- Pick the style and length of the summary.

- Paste the abstract or full text of the research paper.

- Click "Generate Summary".

- View the formatted, structured summary instantly.

- Export the summary as a PDF, Word document.

- Read summary in audio mode.

## Acknowledgements

- LangChain

- Streamlit

- Google Generative AI

- PyMuPDF

- gTTS

## 📄 License


This project is licensed under the MIT License - see the [MIT License](LICENSE) file for details.



