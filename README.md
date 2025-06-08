# NaukariAI - AI Resume Matcher

NaukariAI is a smart resume screening tool that helps recruiters and job seekers by leveraging AI and NLP to match resumes with job descriptions. It automates the resume shortlisting process, highlights skill gaps, and provides detailed feedback, making hiring more efficient and insightful.

---

## 🚀 Features

- Upload resumes and job descriptions (PDF ,DOCX or TXT)
- Extracts and cleans text using NLP preprocessing
- Compares resumes using TF-IDF and cosine similarity
- Identifies and highlights missing skills
- Displays ranked matches with PDF reports

---

## 📌 Problem Statement

Recruiters receive thousands of resumes for each opening, making manual screening time-consuming, biased, and inconsistent. Job seekers are often unaware of missing skills in their resumes.

**NaukariAI solves this by:**

- Matching resumes to job descriptions
- Highlighting skill gaps
- Improving recruiter efficiency
- Helping candidates optimize their resumes

---

## 🧰 Tech Stack

### 🔹 Frontend:
- HTML, CSS, JavaScript

### 🔹 Backend / Python Libraries:
- Flask
- PyPDF2, docx2txt
- scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- reportlab
- os, re, json

---

## 🛠️ Working Flow

1. **Text Extraction** – Extracts resume and JD text
2. **Preprocessing** – Cleans and normalizes data
3. **Resume Matching** – Uses TF-IDF + cosine similarity
4. **Skills Gap Highlighter** – Compares resume vs. JD
5. **Result Display** – Shows top matches and missing skills

## 📸 Screenshots

- ✅ Home Screem
<img width="1439" alt="Screenshot 2025-06-08 at 11 32 29 PM" src="https://github.com/user-attachments/assets/f57d9e73-20c5-456c-b52c-4e5297b12455" />

- ✅ Resume Matching Output 
<img width="1440" alt="Screenshot 2025-06-08 at 11 33 13 PM" src="https://github.com/user-attachments/assets/2e4366b0-f5e6-4aac-a1f0-a6c19959210e" />

- ✅ Generated PDF Report
  <img width="1440" alt="Screenshot 2025-06-08 at 11 33 40 PM" src="https://github.com/user-attachments/assets/c45c8180-8918-40a4-bc5c-f892445b9616" />

---

## 🧪 Future Enhancements

- Integration with job portals
- ATS score checking
- Job recommendations based on resume
- Modern UI using React or Streamlit

---

## ✅ Conclusion

NaukariAI bridges the gap between job seekers and recruiters using intelligent automation. It streamlines hiring by comparing resumes with job descriptions, identifying missing skills, and presenting clear results for better decision-making.

---

> Created by **Atharva Salunkhe**  
