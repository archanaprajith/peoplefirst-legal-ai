# PeopleFirst Legal AI

### Empowering Citizens with Legal Knowledge

> An AI-powered legal guidance platform built to help every Indian citizen understand their rights, navigate legal processes, and access justice — without needing a lawyer.

---

## Screenshots

### Dashboard
![PeopleFirst Legal AI - Dashboard](screenshots/dashboard.png)

### Chat & Features Panel
![PeopleFirst Legal AI - Features](screenshots/features.png)

---

## About the Project

**PeopleFirst Legal AI** is a Flask-based intelligent legal chatbot designed specifically for Indian citizens. It uses Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG) to provide accurate, real-time legal guidance across key areas of Indian law — including cybercrime, women's safety, tenancy rights, consumer protection, and workplace rights.

The platform is built for accessibility, safety, and clarity — breaking down complex legal language into simple, actionable guidance for common people.

---

## Key Features

| Module | Description |
|--------|-------------|
| **Rights Awareness Chatbot** | NLP-powered Q&A using TF-IDF + cosine similarity over a curated Indian legal corpus |
| **Cybercrime Guidance** | Step-by-step evidence checklists for UPI fraud, phishing, identity theft, and ransomware |
| **Women's Safety Module** | POSH Act 2013 guidance, Zero FIR filing assistance, and live emergency helpline detection |
| **Tenancy & Compliance** | Security deposit legal cap calculator under the Model Tenancy Act 2021 |
| **Document Simplifier** | Contract risk analyzer — scores clauses as Red (High) / Amber (Medium) / Green (Safe) |
| **Safety & Privacy Gateway** | Auto PII redaction, legal disclaimer injection, and danger signal interception |

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | Python 3, Flask |
| **NLP / ML** | NLTK, scikit-learn (TF-IDF Vectorizer + Cosine Similarity) |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Data** | Custom Indian Legal Corpus (JSON) |
| **Safety** | Regex-based PII Redactor, Keyword Danger Detector |

---

## Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

**1. Clone the Repository**
```bash
git clone https://github.com/archanaprajith/codealpha_task2.git
cd codealpha_task2
```

**2. Install Dependencies**
```bash
python -m pip install -r requirements.txt
```

**3. Run the Application**
```bash
python app.py
```

**4. Open in Your Browser**
```
http://127.0.0.1:5000
```

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Main dashboard |
| `/chat` | POST | Core legal RAG chatbot |
| `/api/chat_module` | POST | Module-specific chatbot (cybercrime, safety, tenancy) |
| `/api/cybercrime` | POST | Cybercrime evidence checklist generator |
| `/api/tenant_calculator` | POST | Security deposit legal cap calculator |
| `/api/simplify` | POST | Contract and document risk analyzer |
| `/api/safety_logs` | GET | View session safety gateway logs |

---

## Safety & Ethics

PeopleFirst Legal AI is designed with responsible AI principles:

- **PII Redaction** — Automatically detects and masks Aadhaar numbers, PAN cards, and phone numbers from all responses
- **Danger Detection** — Instantly intercepts keywords related to violence or emergencies and displays helpline numbers (112, 1091, 181)
- **Outcome Protection** — Blocks any definitive case outcome predictions to avoid misleading users
- **Disclaimer Injection** — Every AI response includes a statutory legal disclaimer

---

## Applicable Indian Laws Covered

- Bharatiya Nyaya Sanhita (BNS), 2023
- Bharatiya Nagarik Suraksha Sanhita (BNSS), 2023
- Information Technology (IT) Act, 2000
- Protection of Women from Sexual Harassment (POSH) Act, 2013
- Model Tenancy Act, 2021
- Consumer Protection Act, 2019

---

## Legal Disclaimer

> **PeopleFirst Legal AI** is an AI-powered legal information assistant and is **not a substitute for professional legal advice**. All content is provided for educational and awareness purposes only under Indian law. For formal legal representation or advice, please consult a licensed legal professional or advocate.

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

## Author

Developed as part of **CodeAlpha Internship Task 2**
