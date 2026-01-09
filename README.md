# ai-fir-filing-system
A role-based, AI-assisted FIR filing and management web platform enabling citizens to register complaints digitally and police to process FIRs with real-time synchronization.
# AI-Enhanced FIR Filing & Management System

## 📌 Overview
The AI-Enhanced FIR Filing & Management System is a web-based platform designed to digitize and streamline the complaint-to-FIR process. It enables citizens to file complaints online and allows police authorities to review, verify, and assign FIRs in real time through a role-based dashboard system.

The solution improves transparency, efficiency, and accessibility in public safety services while reducing manual delays in FIR registration.

---

## 🚨 Problem Statement
Traditional FIR filing is largely manual, time-consuming, and inconsistent across police stations. Citizens face delays, lack of transparency, and accessibility issues, while police deal with unstructured complaints and inefficient workflows.

---

## 💡 Solution
This platform digitizes the FIR workflow by separating **Complaint Registration** and **FIR Approval**, mirroring real police procedures. It uses AI-assisted logic to categorize complaints, detect emergencies, and prioritize cases, ensuring faster and more transparent processing.

---

## ✨ Key Features
- Online complaint registration
- Role-based dashboards (Citizen & Police)
- Real-time complaint and FIR status tracking
- Evidence upload (photos/videos)
- Multilingual and voice-based input
- Emergency detection and priority tagging
- FIR ID assignment by police
- Auto-generated acknowledgment PDF

---

## 🧠 AI Capabilities
- AI-assisted complaint categorization (rule-based NLP)
- Emergency detection using keyword severity analysis
- Voice-to-text input using Google Speech-to-Text (Web Speech API)

---

## 🏗️ Architecture Overview
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** Firebase Authentication
- **Database:** Cloud Firestore (real-time sync)
- **Storage:** Firebase Storage (evidence files)
- **Hosting:** Firebase Hosting

---

## ☁️ Google Technologies Used
- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- Firebase Hosting
- Google Speech-to-Text (Web Speech API)

---

## 👥 User Roles
### Citizen
- Register complaints
- Upload evidence
- Track complaint & FIR status
- Download acknowledgment PDF

### Police
- View all complaints
- Accept or reject complaints
- Assign FIR ID
- Add police remarks

---

## 🔄 Workflow
1. Citizen submits a complaint
2. Complaint status set to Pending
3. Police review complaint
4. Police accept/reject complaint
5. FIR ID assigned (if approved)
6. Status updated in real time for citizen

---

## 🎯 Innovation Highlights
- Two-stage Complaint → FIR workflow
- Real-time synchronization between citizens and police
- AI-assisted prioritization
- Single app with role-based dashboards

---

## 🚀 Deployment
- Hosted using Firebase Hosting
- Scalable and cloud-native design

---

## 🏆 Hackathon Readiness
- Fully functional prototype
- Realistic government workflow
- High feasibility and social impact
- Demo-ready

---

## 📄 License
This project is created for hackathon and educational purposes.
