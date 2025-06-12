# DataAnalyzer
AI Data Analyst Agent reads CSV, Excel, PDF, DOCX, TXT, and images to extract data and answer with LLaMA 4 Maverick. It supports follow-ups, creates customizable charts, handles Together.ai rate limits, and offers an optional Gradio UI. Built with Python, pandas, matplotlib, seaborn, PyMuPDF, pdfplumber, pytesseract, docx2txt.

🧠 AI-Powered Data Analyst Agent
An intelligent agent that can read any file type — CSV, Excel, PDF, DOCX, TXT, images — and:

✅ Extracts text/data automatically

✅ Answers any question using LLaMA 4 Maverick (meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8)

✅ Supports follow-up Q&A

✅ Creates visualizations with dropdowns for axis selection

✅ Handles Together.ai rate limits with cooldown timer

✅ Clean Gradio UI (but also works without it)

How to Use
STEP 1 Upload any file
STEP 2 Extract content
STEP 3 Ask questions or generate graphs
STEP 4 Wait if cooldown appears (rate-limited model)
STEP 5 Repeat — works like a real data analyst!
STEP 6 Tech Used
Python, Gradio, Together API, pandas, matplotlib, seaborn
STEP 7 Text/image parsing: PyMuPDF, pdfplumber, pytesseract, docx2txt
