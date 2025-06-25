# A Smart Resume Parser

A user-friendly resume parsing web app built using Python and Streamlit. It allows users to upload resumes in PDF, DOCX, or TXT format, extract important details, and generate a summarized report. The app intelligently categorizes skills and provides a downloadable PDF summary.

---

## 🚀 Features

- 📤 Upload PDF, DOCX, or TXT resumes
- 🔍 Extract contact info: Email, Phone, DOB, LinkedIn, GitHub
- 🧠 Summarize resume content using a transformer model
- 🛠️ Categorize skills (Programming, Tools, Soft Skills)
- 📄 Export results to a clean PDF report
- 🧑‍💻 Easy-to-use Streamlit interface

---

## Libraries Used

- **Python**
- **Streamlit** – interactive web UI
- **pdfplumber** – PDF text extraction
- **python-docx** – DOCX text extraction
- **re (regex)** – pattern matching for personal info
- **transformers** – BART model for summarization
- **fpdf** – export structured PDF summary

---

## 📦 Installation

1. Clone the repository:
git clone https://github.com/Phaeyvour/resume-parser-app.git
cd resume-parser-app


Install dependencies:
pip install -r requirements.txt

Run the App Locally
streamlit run app.py