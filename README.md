# 🚀 Job Search Command Center

A serverless, privacy-first career CRM designed to track applications, analyze resume-to-job-description alignment, and generate highly targeted application materials using generative AI.

🔗 **[Launch the Live Web Application](https://mikeylove-997.github.io/Job-suitability-analysis/)**

---

## ✨ Key Features

- 📄 **Multi-Resume Management:** Save and organize up to 10 distinct versions of your CV (e.g., Data Analyst, Software Engineer, Product Manager).
- 🎯 **AI Matcher Engine:** Paste a target job description to calculate a suitability match score, evaluate missing/matching skills, and receive an explicit "Apply, Tweak, or Skip" recommendation.
- 📋 **Application Tracker:** Seamlessly log your job hunt workflow across dynamic status stages (Saved, Applied, Interview, Offer, Rejected).
- 📊 **Career Analytics:** Visualize your weekly outreach activity, pipeline distribution, top targeted companies, and resume optimization history.

---

## 🔒 Security & Privacy Architecture

This application operates as a **100% serverless static app** running entirely in the user's browser client. 

- **Data Ownership:** All resume inputs, tracked applications, and analytics state are persistently held inside your browser's private local memory sandbox (`localStorage`). No personal text is ever synced to an external database.
- **API Key Security:** Users bring their own API key. The key stays completely local to your browser client and is never exposed to the public repository or internet intermediaries.

---

## 🛠️ Getting Started (How to Use)

1. Open the **[Live Application Link](https://mikeylove-997.github.io/Job-suitability-analysis/)**.
2. Head over to **[Google AI Studio](https://aistudio.google.com/)** (free with any standard Google or school credential) and click **Create API Key**.
3. Paste your generated key string into the **API Settings** ribbon at the top of the command center to unlock the AI Matcher.
4. Populate your **Resumes** tab and start conquering your job hunt!

## 🚀 Tech Stack

- **Frontend Core:** React (v18)
- **Styling UI:** Tailwind CSS Framework & Custom Dark-Mode Typography
- **AI Brain Engine:** Google Gemini Pro / Gemini 2.5 Flash API Gateway
- **Data Persistence:** Browser Client LocalStorage API
