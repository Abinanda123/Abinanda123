# Abinanda — Full Stack Developer

CS student at Assam down town University | Placement 2026

## Projects

### 🤖 AI Resume Optimizer — RAG System
An AI-powered job portal that automatically tailors resumes and generates cover letters for specific job listings using RAG architecture.

**What it does:**
- Upload your base resume (PDF) once
- Search real Indian job listings powered by Adzuna API
- AI automatically tailors your resume for each specific job
- Generates a custom cover letter per job application
- Calculates ATS (Applicant Tracking System) score — shows how well your resume matches the job
- Highlights missing keywords recruiters are looking for
- Download tailored resume and cover letter instantly
- Save and manage multiple resume versions

**How the RAG works:**
Resume is chunked into 200-word sections → each chunk converted to 3072-dimension vector embeddings using Gemini API → stored in Pinecone vector database → when a job is selected, job description is converted to embedding → cosine similarity search retrieves the 5 most relevant resume sections → Llama 3 (via Groq) rewrites resume using retrieved context

- **Live:** [https://resume-optimizer-frontend-jade.vercel.app/]
- **Stack:** React · Node.js · Express · MongoDB · Pinecone · Gemini Embeddings · Groq (Llama 3.3 70B) · Adzuna API · JWT Auth · Tailwind CSS · React Router
- **Code:** [Frontend](your frontend repo) | [Backend](your backend repo)

---

### 🔥 Habit Tracker — Full Stack SaaS
A productivity app for tracking daily habits with streak analytics and completion dashboard.

**What it does:**
- Create and manage daily habits
- Mark habits complete each day
- Streak engine — calculates consecutive completion days
- Weekly analytics dashboard showing completion trends
- JWT authentication — each user sees only their own habits
- Fully responsive mobile design

- **Live:** [https://habit-tracker-frontend-nine-lyart.vercel.app](https://habit-tracker-frontend-nine-lyart.vercel.app)
- **Stack:** React · Node.js · Express · MongoDB · JWT · bcrypt · Tailwind CSS
- **Code:** [Frontend](your frontend repo) | [Backend](your backend repo)

---

## Skills
**Frontend:** React · Tailwind CSS · React Router · Axios  
**Backend:** Node.js · Express · REST APIs · JWT Authentication · bcrypt  
**Database:** MongoDB · Mongoose · Pinecone (Vector DB)  
**AI/ML:** RAG Architecture · Vector Embeddings · LLM Integration · Prompt Engineering  
**Tools:** Git · Vercel · Render · MongoDB Atlas · Postman
