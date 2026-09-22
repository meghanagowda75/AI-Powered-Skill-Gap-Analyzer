🌟 **AI Powered Skill Gap Analyzer** 🌟

📘 **Project Overview**

The AI Powered Skill Gap Analyzer is an intelligent web application designed to automatically analyze and compare resumes and job descriptions using Natural Language Processing (NLP) and Machine Learning techniques.
It helps job seekers, recruiters, and HR professionals identify the matching skills, partial overlaps, and missing competencies between a candidate’s resume and a target job role.
By leveraging AI-based embeddings, it computes semantic similarity between skills, generates insightful visualizations, and provides a personalized learning path with estimated durations and recommended resources — empowering users to bridge their skill gaps effectively.

⚡ **Key Features**

✅ **Smart Document Processing**
• Uploads multiple resumes and job descriptions in PDF, DOCX, or TXT format.
• Automatically extracts clean text and removes unnecessary formatting or headers.
• Supports OCR for scanned documents.

✅ **AI-based Skill Extraction**
• Uses spaCy and Sentence-BERT models to identify technical and soft skills.
• Performs keyword and fuzzy matching for accurate skill detection.

✅ **Skill Gap Analysis**
• Compares extracted skills to identify Matched, Partially Matched, and Missing Skills.
• Generates a similarity score to indicate overall alignment between resume and JD.

✅ **Interactive Visualizations**

- 📊 Processing Summary Dashboard: Total Documents, Success Rate, and Failures.
- 📈 Skill Gap Pie Chart: Matched vs Missing skills ratio.
- 🎯 Category Radar Chart: Visual representation of coverage by domain.
- 🔥 Similarity Heatmap: AI-based similarity scores between all skills.

✅****Personalized Learning Path****
• Recommends missing skills with priority, difficulty level, and estimated learning time.
• Provides curated learning resources (Coursera, YouTube, Microsoft Learn, etc.).

✅ **Comprehensive Report Generation**
• Export skill gap results in TXT, CSV, JSON, or PDF formats.
• Ideal for submitting to mentors, recruiters, or for personal improvement tracking.

🧠 **Technologies Used**
- 🖥️ **Frontend & UI:** Streamlit (Python-based Web UI for interactive dashboards)
- 🧩 **NLP & ML:** spaCy, Sentence Transformers *(BERT)*, Scikit-learn
- 📊 **Data Processing:** Pandas, NumPy
- 📄 **Text Extraction:** PyPDF2, python-docx, pytesseract *(OCR)*, pdf2image
- 🔍 **Fuzzy Matching:** fuzzywuzzy *(for approximate text matching)*
- 📈 **Visualization:** Plotly *(Pie, Radar, Heatmap, and Bar Charts)*
- 🧾 **Reports & Export:** ReportLab *(PDF)*, Pandas *(CSV, JSON)*

🎬 **Outputs**

Below are sample output visuals :
- 📤 **Document Upload Interface** – Upload resumes and job descriptions side by side.
- 📊 **Processing Results Dashboard** – Displays total, success, and failure counts.
- 🧾 **Skill Extraction Buttons** – Clean, button-style view of extracted skills.
- 🎯 **Gap Analysis** – Clear distinction of matched, partial, and missing skills.
- 📈 **Radar & Heatmap Visuals** – Compare category-wise and skill-level similarity.
- 🎓 **Personalized Learning Path** – Smart recommendations with duration & resources.

🏁 **Conclusion**

The AI Powered Skill Gap Analyzer provides a data-driven and user-friendly way to measure how well a candidate’s skills align with a job description.

By combining AI embeddings, NLP techniques, and interactive visualization, this tool not only identifies gaps but also guides users on how to close them through personalized learning paths.

This project demonstrates how Artificial Intelligence can revolutionize recruitment and career development — helping both candidates and organizations make smarter, skill-based decisions.

