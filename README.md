# SHCMS
# Smart Hostel Complaint Management System

> **Eliminating the chaos of manual complaints with AI-powered tracking, smart categorization, and automated accountability.**

![License](https://img.shields.io/badge/license-MIT-green) ![Engine](https://img.shields.io/badge/Made%20with-Unity-black) ![Backend](https://img.shields.io/badge/Backend-Firebase-orange) ![AI](https://img.shields.io/badge/AI-Gemini-blue)

## The Problem
Current hostel complaint handling relies on chaotic channels like WhatsApp or manual registers. This leads to:
* **Zero Accountability:** No tracking of who is responsible for fixing issues.
* **Delays:** Critical information reaches authorities too late.
* **Student Frustration:** Students are left in the dark about their complaint status.

## The Solution
**SHCMS** is a cross-platform digital solution connecting Students, Hostel Reps (HR), Wardens, and Principals. It replaces manual logs with a transparent, role-based system that uses **Google Gemini AI** to prioritize issues and **Firebase** to enforce time-bound resolutions.

## Key Features
* **Role-Based Dashboards:** Secure interfaces for Students, HR, Faculty, and Principals.
* **AI Smart Categorization:** Uses **Gemini AI** to auto-classify complaints into *Minor*, *Medium*, or *Critical* tiers.
* **Auto-Approvals:** Minor issues (e.g., fused bulbs) are approved instantly to reduce admin backlog.
* **Time-Bound Escalation:**
    * **> 24 hrs:** Auto-escalates from HR to Warden.
    * **> 48 hrs:** Auto-escalates from Warden to Principal.
* **Privacy First:** Optional **Anonymous Mode** for sensitive complaints to protect student identity.
* **Real-Time Updates:** Live status tracking via Firebase Cloud Messaging.

## Tech Stack
| Component | Technology |
| :--- | :--- |
| **Client Engine** | **Unity Engine (C#)** |
| **Auth** | Firebase Authentication (Email/OTP) |
| **Database** | Cloud Firestore (NoSQL) |
| **Backend Logic** | Firebase Cloud Functions |
| **AI Model** | **Google Gemini Pro** (via API) |
| **Notifications** | Firebase Cloud Messaging (FCM) |

## System Workflow
The system follows a strict logic to ensure speed and transparency:

1.  **Submission:** Student logs in and submits a complaint.
2.  **Analysis:** Gemini AI analyzes the text and assigns a category.
3.  **Routing:**
    * *Minor* → Sent to **HR** (Auto-Approved).
    * *Medium* → Sent to **Warden** for approval.
    * *Critical* → Sent to **Principal** for immediate visibility.
4.  **Resolution:** Staff resolves the issue via their dashboard.
5.  **Escalation:** If the timer expires, the ticket moves up the hierarchy automatically.

## Future Enhancements
* **Multilingual Support** for wider accessibility.
* **Staff Performance Scores** based on resolution speed.
* **ERP Integration** for seamless university management.

## Installation & Setup
The program is still under development so it is not yet deployable

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
