#Mental-Health Integrated Lifestyle & Evaluation Suite

A lightweight, Firebase-powered web application that helps students and young professionals **assess, track, and improve their mental well-being**.  
Core modules include a GAF-based mental-health questionnaire, a personalised dashboard, guided-meditation sessions, a habit tracker with live analytics, journalling, therapist search, and progress insights.:contentReference[oaicite:0]{index=0}

---

## ✨ Key Features
| Module | What it Does |
|--------|--------------|
| **Secure Auth** | Google OAuth & email/password login via Firebase v9.22 SDK.:contentReference[oaicite:1]{index=1} |
| **On-boarding Questionnaire** | Ten-item form maps responses to a Global Assessment of Functioning (GAF) band and stores results for the user.:contentReference[oaicite:2]{index=2} |
| **Personal Dashboard** | Presents current mental-health score, quick links to all self-help tools, and a logout option.:contentReference[oaicite:3]{index=3} |
| **Habit Tracker** | Add, complete, or delete tasks; auto-clears each midnight; renders a real-time pie chart of completed vs pending tasks.:contentReference[oaicite:4]{index=4} |
| **Guided Meditation** | Embedded audio/video sessions for relaxation (placeholder assets; bring your own content). |
| **Daily Journal** | Simple textarea for emotional reflections, timestamped and stored locally (extendable to Firestore). |
| **Therapist Finder** | Static page ready to integrate with third-party therapist directories or your own API. |
| **Progress Insights** | Aggregates scores and habit data for longitudinal trends (under construction). |

---

## 🏗️ Tech Stack

- **Frontend:** HTML 5, CSS 3, vanilla JavaScript (ES Modules)
- **Backend-as-a-Service:** Firebase Authentication & Cloud Firestore
- **Charts:** Chart.js v4
- **Hosting:** Any static host (Firebase Hosting, GitHub Pages, Netlify, Vercel, etc.)

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/smiles-mental-health-platform.git
cd Mental-Health-Platform

# 2. Serve the site (choose ONE)
#    • With VS Code Live Server
#    • python -m http.server 8000
#    • firebase hosting:serve   # if you’re using Firebase Hosting
