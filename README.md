# 🏢 Enterprise Knowledge Management & CRM Architecture (Case Study)

> 🌐 **Live UI Mockup:** [View the Interactive Vercel Prototype](https://inserisci-qui-il-tuo-link.vercel.app)

![System Design](https://img.shields.io/badge/System_Design-Architecture-00599C?style=for-the-badge)
![Business Analysis](https://img.shields.io/badge/Business_Analysis-ROI_Calculation-239120?style=for-the-badge)
![Artificial Intelligence](https://img.shields.io/badge/AI-RAG_%26_LLM-ED8B00?style=for-the-badge)

This repository contains the **System Architecture and Business Case** for an integrated Knowledge Management (KM), CRM, and Learning Management System (LMS) platform powered by AI. This project was developed as part of the Horizon Business Game for STAM S.r.l.[cite: 2].

## 🧠 Proposed Architecture
The platform is designed to act as a *Single Source of Truth* using an advanced Artificial Intelligence pipeline[cite: 2]:
*   **Data Ingestion:** ETL pipelines for unstructured data (SharePoint) and structured legacy systems[cite: 2].
*   **AI Engine (RAG):** An on-premise Large Language Model (LLM) utilizing a Retrieval-Augmented Generation (RAG) backend[cite: 2].
*   **Polyglot Persistence:** Utilizing Vector databases (for embeddings), Relational DBs (for CRM/LMS taxonomy), and Graph databases (for semantic relationships)[cite: 2].

## 🛡️ Security & Privacy
Designed with enterprise constraints in mind:
*   **On-premise deployment:** Ensures strict data sovereignty and GDPR compliance[cite: 2].
*   **Access Control:** Role-Based Access Control (RBAC) enforced directly at the vector database level[cite: 2].
*   **Robustness:** Adversarial testing frameworks to prevent LLM prompt injection and data leaks[cite: 2].

## 📈 Economic Feasibility (ROI)
Beyond technical design, the project includes a full cost-volume analysis[cite: 2]:
*   **Total Estimated Cost:** €222,620 (Infrastructure, Developers, Security Testing)[cite: 2].
*   **Estimated ROI:** 76.90% with a Payback Period of 16 months[cite: 2, 3].
*   **Tax Optimization:** Strategic application of R&D tax credits and the Italian "Patent Box" framework[cite: 2].

## 📂 Project Files
- 📄 [**STAM_Architecture_Business_Report.pdf**](./STAM_Architecture_Business_Report.pdf) - Full architectural design, security protocols, and economic analysis.
- 📊 [**STAM_Pitch_Deck_Presentation.pdf**](./STAM_Pitch_Deck_Presentation.pdf) - Executive presentation and system UI designs.
- 💻 [**index.html**](./index.html) - Tailwind CSS source code for the interactive UI mockup hosted on Vercel.

---
*Developed by: Scandura C., Spolverato T., Sulozequi S., Tonello F., Zenari M.*[cite: 2]