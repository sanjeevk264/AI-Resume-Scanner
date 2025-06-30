# AI Resume Scanner

An intelligent, AI-driven resume screening tool built with Python and BERT. This project evaluates the fit between resumes and job descriptions by leveraging semantic similarity with Sentence-BERT, helping job seekers tailor their resumes more effectively by identifying missing keywords and skill gaps.

🔍 Core Features
✅ Extracts text from multiple resume formats including PDF, DOCX, and TXT

✅ Parses job descriptions to analyze key requirements

✅ Computes semantic similarity scores using Sentence-BERT embeddings

✅ Highlights important keywords absent from the resume

🧠 Designed for easy extension with a potential Streamlit UI and cloud deployment
## 📂 Project Layout

```
AI-Resume-Scanner/
├── app/
│   ├── resume_parser.py
│   ├── job_parser.py
│   └── __init__.py
├── data/
│   ├── resumes/
│   └── job_descriptions/
├── main.py                  # Core semantic similarity logic
├── requirements.txt
└── README.md

```

## ⚙️ How to Use

1. Clone the repository:
```bash
git clone https://github.com/SanjeevKadam/AI-Resume-Scanner.git
cd AI-Resume-Scanner

```

2. Install dependencies:
```bash
pip install -r requirements.txt

```

3. Add your resume and job description (in `data/`)

4. Run the main script to get match scores and keyword insights:
```bash
python3 main.py
```

🤖 AI-Powered Semantic Matching
This tool leverages the sentence-transformers library to transform resumes and job descriptions into vector embeddings, enabling a nuanced similarity comparison beyond keyword matching.
### Example Output:
```
Semantic Match Score: 88.42%
Keywords Missing from Resume:
cloud, deployment, scalability, teamwork, communication

```

🚀 Planned Improvements
Interactive Streamlit-based UI for resume and job upload

Cloud deployment on AWS or Streamlit Cloud for easy access

Enhanced keyword feedback and resume tailoring recommendations

Integration with Google Cloud AI services

👨‍💻 About the Developer
Sanjeev Kadam
AI enthusiast passionate about leveraging NLP and machine learning to improve job search experiences.

---
