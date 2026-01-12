📄🤖 AI-Powered Resume Screener

This project is an AI-powered resume ranking system that analyzes multiple resumes and compares them against a job description to find the best match. It uses NLP, embeddings, and cosine similarity to measure how closely each resume aligns with job requirements.

🚀 Features

✨ Upload multiple resumes (PDF / DOCX / TXT)
✨ Upload one job description
✨ Automatic text extraction
✨ Embedding generation using Sentence Transformers
✨ Resume ranking using cosine similarity
✨ Output sorted from best-match to lowest

🧠 How It Works

📥 User uploads:

1 job description

Multiple resumes

🔍 The system extracts text using:

pypdf → PDF

python-docx → DOCX

Raw TXT

🧠 Text converted to vector embeddings using:

all-MiniLM-L6-v2 model

📊 Cosine similarity is calculated:

Higher score = better resume match

🏆 Resumes ranked and displayed

🧰 Technologies Used
Technology	Purpose
🧠 Sentence Transformers	Embeddings
🔢 Cosine Similarity	Ranking
📄 pypdf	Extract PDF text
📝 python-docx	Extract DOCX text
🔥 PyTorch	Model backend
☁️ Google Colab	Simple execution
