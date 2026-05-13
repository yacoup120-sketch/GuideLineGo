# ⚕️ GuidelineGo
**Unified MedPharm Clinical Decision Support System (CDSS)**

GuidelineGo is an advanced, AI-powered healthcare application designed to streamline clinical workflows for both **Physicians (MD)** and **Pharmacists (PharmD)**. Developed to enhance healthcare employability and reduce clinical errors, this system bridges the gap between medical diagnostics and pharmaceutical care.

## 🚀 Project Overview
In modern healthcare, interdisciplinary collaboration is key. GuidelineGo provides a unified dashboard that adapts to the user's role:
* **For Physicians:** Offers step-by-step guidance through established clinical protocols (e.g., Hypertension, Asthma).
* **For Pharmacists:** Provides an interactive workspace for OTC Triage, Drug-Drug Interaction (DDI) checks, and patient counseling.

## ✨ Key Features
* **Dual-Engine AI:** Powered by LLaMA 3.1, the system seamlessly switches between a diagnostic medical persona and a medication-expert pharmacist persona.
* **Interactive OTC Triage:** Guides the pharmacist through a logical sequence of questions to identify minor ailments and recommend appropriate generic treatments.
* **Patient Medication Schedules:** Automatically generates structured, easy-to-read markdown tables containing the drug generic name, dosage, frequency, and instructions.
* **EHR Export & Printing:** A built-in feature to print clinical reports and patient schedules seamlessly, omitting UI clutter for official documentation.
* **Secure API Key Management:** Uses browser `localStorage` to securely manage API keys without hardcoding them into the repository.

## 🛠️ Technology Stack
* **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+).
* **AI Engine:** Groq API leveraging the ultra-fast `llama-3.1-8b-instant` model.
* **Markdown Parsing:** [Marked.js](https://marked.js.org/) for rendering clinical tables and formatted text.

## 🔮 Future Development (Phase 2)
As a Minimum Viable Product (MVP), the current system relies on generic drug names to ensure 100% clinical accuracy. Future updates will include:
1. Integration with the **Jordanian Food and Drug Administration (JFDA)** and **JPA** databases to provide exact local commercial brands.
2. User authentication and real-time Electronic Health Record (EHR) integration.

## 💻 How to Use
1. Open the [Live Demo](https://yacoup120-sketch.github.io/GuidelineGo/).
2. Upon first launch, enter your **Groq API Key**.
3. Select a Quick Prompt from the bottom menu or type a custom clinical scenario.
4. Click **Print Patient Schedule** to generate a clean, printable clinical report.

---
*Developed with 💡 for the AI & Employability Hackathon.*
