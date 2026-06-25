📌 Project Overview

The Cognitive Resume Fit Analyzer (CRFA) is an AI-powered resume screening system that intelligently evaluates and ranks candidates based on their relevance to a given job description. The project leverages Natural Language Processing (NLP), Sentence Transformers, and a hybrid scoring model to automate the candidate screening process, reducing manual effort and improving recruitment efficiency. The system computes semantic similarity, skill relevance, and work experience to generate a comprehensive AI Fit Score for each applicant.

🎯 Project Objectives
Automate resume screening using Artificial Intelligence.
Compare resumes with job descriptions using semantic understanding.
Evaluate candidates based on skills and experience.
Generate an explainable AI-based ranking system.
Visualize candidate rankings for better hiring decisions.
🚀 Features
AI-powered resume screening
Semantic similarity using Sentence Transformers
Skill-based weighted scoring
Experience extraction using Regular Expressions (Regex)
Hybrid AI Fit Score calculation
Candidate ranking and visualization
Modular and scalable architecture
Google Colab implementation
🛠️ Technologies Used
Python
Sentence Transformers
Hugging Face
NLP (Natural Language Processing)
Pandas
NumPy
Matplotlib
Regular Expressions (Regex)
Google Colab
⚙️ AI Scoring Methodology

The final candidate ranking is calculated using a hybrid weighted scoring model:

Final AI Fit Score = (0.5 × Semantic Similarity) + (0.3 × Skill Score) + (0.2 × Experience Score)

Evaluation Parameters
Semantic Similarity (50%) – Measures contextual similarity between the resume and job description using transformer embeddings.
Skill Relevance (30%) – Evaluates the presence of required technical skills.
Experience Score (20%) – Scores candidates based on years of professional experience extracted using Regex.
📊 Workflow
Input Job Description
Load Candidate Resumes
Clean and Normalize Text
Extract Experience using Regex
Generate Sentence Embeddings
Calculate Semantic Similarity
Compute Skill Score
Calculate Final AI Fit Score
Rank Candidates
Visualize Results using Bar Charts
📈 Results

The system successfully ranks candidates according to their overall suitability for a job role. It combines semantic matching, technical skills, and experience into a single AI Fit Score and presents the results in both a ranked table and graphical visualization for easy interpretation.

💡 Key Learning Outcomes
Natural Language Processing (NLP)
Sentence Embeddings
Semantic Search
AI-Based Resume Screening
Explainable AI
Text Cleaning & Preprocessing
Feature Engineering
Candidate Ranking Algorithms
Data Visualization
AI Recruitment Systems
📚 Future Enhancements
Support real PDF and DOCX resumes
Resume parsing using OCR
Named Entity Recognition (NER)
Streamlit web application deployment
Resume recommendation engine
LLM-powered resume analysis
Integration with Applicant Tracking Systems (ATS)
🔑 Key Skills
Python
Artificial Intelligence (AI)
Natural Language Processing (NLP)
Sentence Transformers
Hugging Face
Semantic Search
Machine Learning
Resume Parsing
Regex
Pandas
NumPy
Matplotlib
Data Visualization
Candidate Ranking
Explainable AI
Google Colab
