# Stop Hardcoding AI Prompts: Building Secure, Production-Ready AI Apps with Firebase

<img width="1024" height="576" alt="image" src="https://github.com/user-attachments/assets/32ee1800-c08d-49fc-af6b-dc0fd8e514ef" />


**Hosted by:** GDG On Campus JIS University in collaboration with GDG On Campus IIIT Kalyani

## 📖 About This Event

Step into the world of production-grade generative AI in this hands-on online session. Hardcoding AI prompts directly into your frontend leaves applications exposed to prompt injection vulnerabilities, unauthorized API abuse, and rigid deployment cycles. 

Move beyond basic prototypes and learn how to architect and deploy a real-world, fully serverless AI Expense & Receipt Compliance Auditor. Whether you're building your first AI-powered app or looking to harden existing architectures for scale, this session is your blueprint for shipping secure, enterprise-ready AI with Firebase!

### What We’ll Cover:
* **Prompt & API Security:** Protect sensitive Gemini instructions from client-side exposure using Server Prompt Templates and Firebase App Check.
* **Deterministic Structured Outputs:** Enforce strict schema validation to ensure reliable, predictable JSON responses for production apps.
* **Zero-Downtime Model & Prompt Updates:** Decouple prompt engineering from your release cycle—test, iterate, and switch AI models live in production without app redeployments.
* **End-to-End Serverless Architecture:** Integrate Firebase AI Logic and Cloud Firestore to build scalable, low-maintenance AI workflows.

---

## 🎙️ Speaker

**Debajit Mallick**  
*Senior Software Engineer at Quadrant Technologies*  
🔗 [Connect on LinkedIn](https://www.linkedin.com/in/debajit-mallick/)

---

## 📺 Session Recording & Summary

**Watch the full session here:** [YouTube Video Link](https://www.youtube.com/watch?v=SxdQu7LI4ss)

This session provides a comprehensive guide on building secure, production-ready AI applications using Firebase. The core focus is moving away from "toy" AI demos toward robust enterprise-grade architectures.

### ⏱️ Timestamps & Core Concepts

#### Core Concepts and Architecture
* **11:20 - 14:15 | The Problem with Hardcoding:** The speaker explains why hardcoding prompts in the frontend is a security risk, leading to issues like prompt injection, instruction leaks, and exposed API keys.
* **14:15 - 16:20 | The Firebase Approach:** Instead of building custom backend APIs, developers can use Firebase services—specifically AI Logic, App Check, and Authentication—to create a secure, serverless infrastructure.
* **18:40 - 19:55 | High-Level Design:** The workflow involves: User Login (Firebase Auth) → App Check verification → Sending input to Firebase AI Logic → Processing via server-side prompt templates → Storing validated results in Firestore.

#### Security and Management Strategies
* **21:04 - 23:50 | Locking Prompts:** By moving prompt templates to the backend, you prevent users from inspecting or modifying prompts via the browser's network tab.
* **25:17 - 27:10 | Firestore Security Rules:** These rules allow developers to enforce role-based access, ensuring only authorized personnel (e.g., managers) can perform sensitive actions like updating bill statuses.

<img width="1024" height="510" alt="image" src="https://github.com/user-attachments/assets/da9630c7-3282-4832-b74a-12fff4213c6d" />


* **28:18 - 34:00 | Remote Config:** This tool allows for live updates to app configuration and AI models without requiring a full redeployment of the application.

#### Key Takeaways for Developers

<img width="1024" height="507" alt="image" src="https://github.com/user-attachments/assets/719d65d6-de28-4b51-96cd-b3284e4e7932" />


* **40:53 | Treat prompts as backend code:** Never ship them in client-side bundles.
* **41:22 | Layer your security:** Use App Check and strict JSON schemas to ensure deterministic AI output.
* **42:40 | Leverage the Spark Plan:** Developers can prototype these features for free using Firebase's generous entry-level tier.

---

## ❓ Q&A and Connect

<img width="1024" height="673" alt="image" src="https://github.com/user-attachments/assets/35b44fc8-1ed6-4b65-a4fa-6dd4c303b894" />


---
