# SHCMS

# 🎓 SHCMS - Smart Hostel Complaint Management System

> **Eliminating the chaos of manual complaints with AI-powered tracking, smart categorization, and automated accountability.**

![License](https://img.shields.io/badge/license-MIT-green) ![Engine](https://img.shields.io/badge/Made%20with-Unity-black) ![Backend](https://img.shields.io/badge/Backend-Firebase-orange) ![AI](https://img.shields.io/badge/AI-Gemini-blue)

## 🚩 The Problem
[cite_start]Current hostel complaint handling relies on chaotic channels like WhatsApp or manual registers[cite: 5]. This leads to:
* [cite_start]**Zero Accountability:** No tracking of who is responsible for fixing issues[cite: 6].
* [cite_start]**Delays:** Critical information reaches authorities too late[cite: 8].
* [cite_start]**Student Frustration:** Students are left in the dark about their complaint status[cite: 11].

## 💡 The Solution
[cite_start]**SHCMS** is a cross-platform digital solution connecting Students, Hostel Reps (HR), Wardens, and Principals[cite: 14]. It replaces manual logs with a transparent, role-based system that uses **Google Gemini AI** to prioritize issues and **Firebase** to enforce time-bound resolutions.

## ✨ Key Features
* [cite_start]**🔐 Role-Based Dashboards:** Secure interfaces for Students, HR, Faculty, and Principals[cite: 55].
* [cite_start]**🤖 AI Smart Categorization:** Uses **Gemini AI** to auto-classify complaints into *Minor*, *Medium*, or *Critical* tiers[cite: 30, 78].
* [cite_start]**⚡ Auto-Approvals:** Minor issues (e.g., fused bulbs) are approved instantly to reduce admin backlog[cite: 33, 56].
* **⏳ Time-Bound Escalation:**
    * [cite_start]**> 24 hrs:** Auto-escalates from HR to Warden[cite: 46].
    * [cite_start]**> 48 hrs:** Auto-escalates from Warden to Principal[cite: 48].
* [cite_start]**🛡️ Privacy First:** Optional **Anonymous Mode** for sensitive complaints to protect student identity[cite: 62].
* **📢 Real-Time Updates:** Live status tracking via Firebase Cloud Messaging.

## 🏗 Tech Stack
| Component | Technology |
| :--- | :--- |
| **Client Engine** | **Unity Engine (C#)** |
| **Auth** | Firebase Authentication (Email/OTP) |
| **Database** | Cloud Firestore (NoSQL) |
| **Backend Logic** | Firebase Cloud Functions |
| **AI Model** | **Google Gemini** (via API) |
| **Notifications** | Firebase Cloud Messaging (FCM) |

## ⚙️ System Workflow
The system follows a strict logic to ensure speed and transparency:

1.  **Submission:** Student logs in and submits a complaint.
2.  **Analysis:** Gemini AI analyzes the text and assigns a category.
3.  **Routing:**
    * [cite_start]*Minor* → Sent to **HR** (Auto-Approved)[cite: 33].
    * [cite_start]*Medium* → Sent to **Warden** for approval[cite: 34].
    * [cite_start]*Critical* → Sent to **Principal** for immediate visibility[cite: 37].
4.  **Resolution:** Staff resolves the issue via their dashboard.
5.  [cite_start]**Escalation:** If the timer expires, the ticket moves up the hierarchy automatically[cite: 50].

## 🔮 Future Enhancements
* [cite_start]**Multilingual Support** for wider accessibility[cite: 78].
* [cite_start]**Staff Performance Scores** based on resolution speed[cite: 78].
* [cite_start]**ERP Integration** for seamless university management[cite: 79].

## 📦 Installation & Setup
Program still under development and not yet deployable

## 📄 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
