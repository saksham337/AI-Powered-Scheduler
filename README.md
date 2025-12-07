# 🤖 AI-Recruiter


![WhatsApp Image 2025-12-07 at 19 21 48_7454a129](https://github.com/user-attachments/assets/9c530eb9-6314-480c-bb8c-815711fb34eb)

![WhatsApp Image 2025-12-07 at 19 21 48_0c15e265](https://github.com/user-attachments/assets/0447c759-b494-49ce-bee5-ea18bf8585a7)



**AI-Recruiter** is an AI-powered recruitment automation platform developed to streamline and enhance the hiring process. Leveraging state-of-the-art technologies like Large Language Models (LLMs), RAG (Retrieval-Augmented Generation), and voice AI, it offers recruiters and candidates a fully automated, intelligent, and voice-interactive interview experience.

Visit ```https://ai-recruiter-pi.vercel.app``` to access the live web application.

---

## 🚀 Features

* 🎯 **AI-Generated Interviews**: Automatically generates contextual and role-based interview questions.
* 🗣️ **Voice Interviewing with AI**: Conducts interactive, human-like voice interviews powered by Vapi.ai.
* 📊 **Recruiter Dashboard**: Manage job roles, questions, candidate sessions, and insights from a central dashboard.
* 🔗 **Unique Interview Links**: Share interviews with candidates via unique, secure links.
* 🤖 **Automated Evaluation**: AI evaluates candidate responses and generates performance summaries for recruiters.

---

## 🧑‍💼 User Workflows

### ✅ Recruiter

* Secure login via Supabase Auth (Google OAuth supported).
* Create interview templates for different job roles.
* View and analyze interview responses via a custom dashboard.
* Share interview URLs with candidates.

### 🎙️ Candidate

* Receive a voice-interactive interview via a secure link.
* Answer AI-generated questions in real time using voice.
* Responses are recorded, transcribed (via Deepgram), and evaluated.

---

## 🏗️ Tech Stack

| Layer              | Tech Used                                                                       |
| ------------------ | ------------------------------------------------------------------------------- |
| **Frontend**       | Next.js 15.2.4, React 18, Radix UI, Tailwind CSS                                |
| **Animations**     | Framer Motion, Lottie                                                           |
| **Voice AI**       | Vapi.ai (voice interaction), Deepgram (speech-to-text), PlayHT (text-to-speech) |
| **Authentication** | Supabase Auth + Google OAuth                                                    |
| **Backend DB**     | Supabase (PostgreSQL + Realtime)                                                |
| **AI Integration** | OpenAI API for interview logic and assessments                                  |
| **State Mgmt**     | React Context API                                                               |

w








