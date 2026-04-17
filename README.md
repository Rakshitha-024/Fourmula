# Fourmula
# 🛡️ AegisLex

### **AI-Assisted Domestic Violence Case Pattern Analyzer for Legal Aid Organizations**

## 📌 Project Overview

**AegisLex** is a privacy-preserving AI platform designed to assist Legal Aid NGOs and lawyers in analyzing domestic violence case data. By transforming fragmented victim statements and intake forms into structured legal insights, AegisLex helps overburdened professionals prioritize high-risk situations and prepare for hearings with greater speed and accuracy.

## 🎯 Problem Statement

Legal aid organizations often face a massive influx of data including:
* **Structured intake forms** and case history timelines.
* **Unstructured free-text** victim statements and police reports.

**The Challenge:** Manual analysis is time-consuming, error-prone, and difficult to scale. 
**The Solution:** AegisLex automates pattern detection, severity classification, and legal brief generation to improve intervention speed.

---

## 🚀 Key Features

### 🧠 AI Case Analysis
* **Severity Classification:** Instant risk tiering based on reported incidents.
* **Escalation Prediction:** Identifies markers that suggest a high probability of future violence.
* **Pattern Recognition:** Detects specific abuse types (Financial, Physical, Emotional, Coercive Control).

### 💬 AI Legal Assistant & Voice
* **Context-Aware Chat:** Real-time guidance for legal professionals during intake.
* **Voice Interface:** Hands-free interaction using the Web Speech API for better accessibility.

### ⚖️ Legal Case Summary Generator
Automatically generates a professional brief including:
* Incident summaries and risk indicators.
* Suggested legal sections (e.g., IPC/BNS references).
* Recommended immediate actions.

### 🔐 Privacy-First Design
* **Data Anonymization:** Built to process data without storing personally identifiable information (PII).
* **Local Processing Support:** Designed for secure, ethical legal environments.

---

## ⚙️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Backend** | Node.js, Express.js |
| **AI/NLP** | OpenAI API (GPT-4o / GPT-4o Mini) |
| **Voice** | Web Speech API (Speech Recognition & Synthesis) |

---

## 🛠️ Installation Guide

Follow these steps to get a local instance of AegisLex running:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/aegislex.git
   cd aegislex
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment**
   Create a `.env` file in the root directory and add your OpenAI key:
   ```env
   OPENAI_API_KEY=your_api_key_here
   PORT=3000
   ```

4. **Start the Server**
   ```bash
   node server.js
   ```

5. **Launch the App**
   Open `http://localhost:3000` (or your local file path) in your browser.

---

## 📊 Evaluation Metrics
To ensure the tool provides high-quality legal support, we measure:
* **Classification Accuracy:** Precision in identifying abuse categories.
* **Recall:** Ensuring no high-risk indicators are missed in long statements.
* **Brief Completeness:** The percentage of required legal sections successfully populated by AI.

---

## 🔮 Future Enhancements
* **Multi-language Support:** Enabling intake in local dialects and regional languages.
* **Visual Timelines:** Interactive UI to map the history of abuse over time.
* **Lawyer Collaboration:** A secure dashboard for multiple attorneys to track a single case.
* **Offline Support:** Local LLM integration for sensitive environments without internet access.

---
NSE file for details.

## ❤️ Acknowledgements
* Legal Aid Organizations providing feedback on real-world workflows.
* The domestic violence awareness initiatives that inspire this work.

---
**🛡️ AegisLex** | *AI for Safer Lives. Smarter Legal Aid.*
