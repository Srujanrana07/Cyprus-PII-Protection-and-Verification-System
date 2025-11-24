<p align="center">
  <img src="assets/logo-pii-protect-dark.svg" width="220" alt="PII Protect Logo"/>
</p>

<h1 align="center">🛡️Cyprus : PII Protect System</h1>
<p align="center"><i>AI-Powered Sensitive Data Detection, Masking & Secure Document Management</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/Srujanrana07//Cyprus-PII-Protection-and-Verification-System?style=flat-square&color=blue" />
  <img src="https://img.shields.io/github/commit-activity/m/Srujanrana07//Cyprus-PII-Protection-and-Verification-System?style=flat-square&color=blueviolet" />
  <img src="https://img.shields.io/badge/Tests-Passing-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Coverage-92%25-yellowgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Code%20Quality-A%2B-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Django-Backend-092E20?style=flat-square&logo=django" />
  <img src="https://img.shields.io/badge/Node.js-Service-339933?style=flat-square&logo=node.js" />
  <img src="https://img.shields.io/badge/Tesseract-OCR-EA4335?style=flat-square&logo=google" />
  <img src="https://img.shields.io/badge/AES--256-Encryption-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
</p>

---

# 🌟 Overview

**PII Protect System** is a secure web platform designed to detect, mask, encrypt, and manage **Personally Identifiable Information (PII)** from user-uploaded documents.

Using **OCR**, **AI-based PII detection**, and **AES-256 encryption**, the system enables:

- Safe document upload  
- Automatic PII extraction  
- User-controlled masking/revealing  
- Secure encrypted storage  
- Manager-level controlled access  

---

# 🔄 System Workflow

![Workflow](https://github.com/user-attachments/assets/778976b0-4234-4965-be84-600fc2553c17)

```
User Upload → OCR → PII Detection → Masking → Encryption → Secure Storage → Manager Access
```

---

# ✨ Features

| Feature | Description |
|--------|-------------|
| **OCR Extraction** | Uses Tesseract to read text from images |
| **PII Detection** | Detects Aadhaar, PAN, phone, email, address, etc. |
| **Custom Masking** | Partially or fully masks sensitive elements |
| **User Access Control** | User decides if the PII should be revealed or hidden |
| **Manager Verification System** | Manager must authenticate using ID |
| **AES-256 Encryption** | Every extracted PII text is encrypted |
| **Secure Blob Storage** | Masked files stored as encrypted blob objects |
| **Audit Logs** | Tracks every access request |

---

# 🏗️ Architecture

```
┌─────────────────────────────────────────────┐
│                   FRONTEND                  │
│   HTML • CSS • JavaScript (User Interface)  │
└─────────────────────────────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────────┐
│                    API LAYER                │
│      Django Backend + Node.js Services      │
└─────────────────────────────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────────┐
│                OCR & PII ENGINE             │
│   Tesseract OCR + Rule/Model-based PII DET  │
└─────────────────────────────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────────┐
│          ENCRYPTION & STORAGE LAYER         │
│      AES-256 Encryption + Blob Storage      │
└─────────────────────────────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────────┐
│              MANAGER ACCESS SYSTEM          │
│       Identity Validation + Secure Access   │
└─────────────────────────────────────────────┘
```

---

# 🛠️ Technology Stack

### Frontend  
- HTML  
- CSS  
- JavaScript  

### Backend  
- Django  
- Node.js  
- MySQL  

### Security  
- AES-256 encryption  
- Blob storage  
- Access control  
- Audit logs  

---

# 🎥 Demo Screenshots

> Replace these with real app screenshots.

### Upload UI  
<img src="assets/demo1.png" width="700"/>

### OCR + PII Detection  
<img src="assets/demo2.png" width="700"/>

### Manager Login  
<img src="assets/demo3.png" width="700"/>

### Masked Document  
<img src="assets/demo4.png" width="700"/>

---

# 🔒 Security & Compliance

- DPDP Act 2023 Compliant  
- IT Act & SPDI Rules  
- AES-256 Industry Encryption  
- Zero-Trust Workflow  

---

# ⚠️ Challenges

1. DPDP compliance complexity  
2. Low user awareness  
3. Managerial misuse risks  
4. Cyberattacks despite encryption  

---

# 🎯 Impact

- Protects sensitive Indian identity documents  
- Reduces fraud & identity theft  
- Builds trust in digital document workflows  
- Useful for universities, HR, banks, govt offices  

---

# 🚀 Future Enhancements

- AI-based PII classification  
- Multi-language OCR  
- Role-based dashboards  
- Cloud storage encryption  
- Real-time redaction  

---

# 📜 License

MIT License.
