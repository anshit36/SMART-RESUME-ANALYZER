# Smart Resume Analyzer 📄🤖

An AI-powered web application built with **Python and Streamlit** that analyzes resumes, extracts relevant information, evaluates skills, provides career-oriented insights, and helps users identify suitable courses and areas for improvement.

The project is designed to make the resume-review process faster and more informative for students, freshers, and job seekers.

## 🚀 Features

* 📄 **Resume Upload** — Upload a resume and analyze its contents.
* 🔍 **Resume Analysis** — Extract and analyze important information from the uploaded resume.
* 🧠 **Skill Analysis** — Identify relevant technical and professional skills.
* 📊 **Resume Evaluation** — Analyze the resume and provide useful insights.
* 💼 **Career Recommendations** — Suggest areas for improvement based on the resume.
* 📚 **Course Recommendations** — Provide relevant course suggestions to help users improve their skills.
* ▶️ **YouTube Resources** — Provide useful learning resources for recommended skills.
* 🖥️ **Interactive Streamlit Interface** — Simple and user-friendly web interface.
* 🖼️ **Visual Dashboard** — Includes visual elements to make the analysis easier to understand.

## 🛠️ Tech Stack

### Programming Language

* Python

### Framework

* Streamlit

### Libraries & Tools

* Pandas
* NLTK
* PyResParser
* PDFMiner
* Plotly
* Streamlit Tags
* Pillow
* Pafy / YouTube-related libraries

The complete dependency list is available in [`requirements.txt`](Smart_Resume_Analyser_App/requirements.txt).

## 📁 Project Structure

```text
Smart-Resume-Analyser/
│
├── Smart_Resume_Analyser_App/
│   ├── Logo/
│   │   ├── SRA_Logo.ico
│   │   └── SRA_Logo.jpg
│   │
│   ├── App.py
│   ├── Courses.py
│   ├── README.md
│   ├── requirements.txt
│   ├── sc1.png
│   ├── sc2.png
│   └── yt_thumb.jpg
│
├── .gitignore
└── README.md
```

> **Note:** Uploaded resumes, virtual environments, Python cache files, and other personal/generated files are excluded from the GitHub repository using `.gitignore`.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/22rohanbisht-ally/Smart-Resume-Analyser.git
```

### 2. Navigate to the project

```bash
cd Smart-Resume-Analyser
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

If PowerShell blocks activation, you can temporarily allow script execution for the current terminal session:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then activate again:

```powershell
venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r Smart_Resume_Analyser_App/requirements.txt
```

### 6. Run the application

```bash
streamlit run Smart_Resume_Analyser_App/App.py
```

The application should then open in your browser at the local Streamlit address.

## 🎯 How It Works

The general workflow of the application is:

```text
Upload Resume
      ↓
Extract Resume Content
      ↓
Analyze Resume Information
      ↓
Identify Skills & Profile
      ↓
Generate Career Insights
      ↓
Recommend Courses & Resources
```

The application combines resume parsing, text processing, skill analysis, and recommendation features into a single interactive interface.

## 👨‍💻 Use Cases

This project can be useful for:

* 🎓 Students preparing their first resume
* 💼 Freshers applying for internships and jobs
* 📄 Job seekers reviewing their resumes
* 🧑‍💻 Developers looking to identify missing technical skills
* 📚 Learners searching for courses related to their career goals

## 🔮 Future Improvements

Some possible improvements for future versions include:

* [ ] Add an AI/LLM-powered resume feedback system
* [ ] Add ATS compatibility scoring
* [ ] Improve skill extraction using modern NLP models
* [ ] Add job-description vs. resume matching
* [ ] Generate personalized learning roadmaps
* [ ] Add resume improvement suggestions section-by-section
* [ ] Add support for more resume formats
* [ ] Deploy the application publicly
* [ ] Improve the UI/UX and visualization dashboard

## 🔐 Privacy

Uploaded resumes may contain personal information. For this reason, user-uploaded resume files are **not included in this GitHub repository**.

The `Uploaded_Resumes/` directory is excluded through `.gitignore`.

Users should also avoid storing passwords, API keys, database credentials, or other sensitive information directly in the source code.

## 📌 Project Status

**Status:** Completed / Academic & Portfolio Project

This project was developed to explore **Python, Streamlit, NLP, resume parsing, data processing, and recommendation systems** through a practical application.



### 🔗 GitHub


https://github.com/anshit36/SMART-RESUME-ANALYZER/edit/main/README.md
---

⭐ If you find this project useful, consider giving the repository a star!
