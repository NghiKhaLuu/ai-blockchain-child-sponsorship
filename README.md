# AI & Blockchain-Based Transparent Child Sponsorship System

## Introduction
In the context of rapid digital transformation, social sponsorship programs for underprivileged children require a higher level of transparency, accountability, and efficiency. 

However, many existing systems still face critical limitations such as:
- Lack of transparency in fund management
- Difficulty in tracking financial flows
- Limited ability to verify receipts and transactions
- Weak trust between donors, authorities, and beneficiaries

This project aims to address these challenges by proposing an integrated system that leverages Artificial Intelligence (AI) and Blockchain technology to enhance transparency and trust in sponsorship activities.

---

## Objectives
The main objectives of this project include:

- Applying AI for fraud detection, receipt verification, and transaction validation
- Utilizing Blockchain to ensure data integrity, immutability, and transparency
- Developing an integrated web and mobile platform for all stakeholders
- Designing a controlled wallet system for each beneficiary
- Proposing a scalable and practical solution for real-world deployment in Vietnam

---

## Problem Statement
Current sponsorship systems face several key issues:

### 1. Lack of Transparency
Many charity programs rely on manual processes, making it difficult for donors to track how their funds are used.

### 2. Difficulty in Verifying Expenses
Receipts and documents are often processed manually, leading to risks of duplication, fraud, or manipulation.

### 3. No Immutable Audit Mechanism
Data can be altered or lost, reducing the reliability of transaction history.

### 4. Fragmented Systems
There is no unified platform connecting donors, beneficiaries, and authorities.

---

## Proposed Solution
This project introduces a digital platform that integrates:

- **Artificial Intelligence (AI)** for automated verification and fraud detection
- **Blockchain** for immutable transaction recording
- **Web & Mobile Applications** for real-time interaction and monitoring

---

## User Roles
The system is designed for five main user groups:

- Donor
- Beneficiary
- Local Authority
- Provincial Authority
- System Administrator

---

## System Architecture
The system follows a **three-tier architecture**:

### 1. Presentation Layer
- Web platform for administrators and authorities
- Android application for donors and beneficiaries

### 2. Application Layer
- Business logic processing
- AI module for receipt verification
- Blockchain integration for transaction hashing
- RESTful APIs for communication

### 3. Data Layer
- MySQL database for structured data storage
- Blockchain (Ethereum/Polygon Testnet) for transaction hash storage

---

## Key Features

### AI Module
- OCR (Optical Character Recognition) for extracting receipt data
- Deep Learning models (CNN) for fraud detection
- Risk scoring system for transaction monitoring

### Blockchain Integration
- Transaction hashing using SHA-256
- Immutable and verifiable records
- Public verification for donors

### Smart Wallet System
- Monthly spending limits per child
- Transaction monitoring and validation
- Automatic alerts for suspicious activities

---

## System Workflow
1. Donor selects a beneficiary and makes a donation  
2. Transaction is recorded in the system  
3. AI verifies submitted receipts  
4. Transaction hash is stored on Blockchain  
5. Authorities review flagged transactions  
6. Donor can track fund usage transparently  

---

## AI Approach
The AI module consists of two main stages:

- **OCR Processing**: Extract text data from receipts using Tesseract OCR
- **Fraud Detection**: Use CNN models (ResNet/MobileNet) to detect anomalies or manipulation

---

## Blockchain Approach
- Each transaction is converted into a hash (SHA-256)
- The hash is recorded on Ethereum/Polygon testnet
- Ensures immutability and auditability

---

## Technologies Used

| Component        | Technology |
|-----------------|-----------|
| Frontend        | HTML, CSS, Bootstrap, JavaScript |
| Backend         | PHP / Python Flask |
| Database        | MySQL |
| Mobile App      | Android (Kotlin/Java) |
| AI Module       | Python, OpenCV, Tesseract OCR, CNN |
| Blockchain      | Ethereum / Polygon, Web3 |
| Deployment      | XAMPP, Firebase, Render |

---

## Expected Outcomes
- A functional prototype integrating Web + Mobile + AI + Blockchain
- Improved transparency and trust in sponsorship activities
- Automated fraud detection and verification process
- A pilot-ready model for local deployment

---

## Future Development
- Expand to mobile-first architecture
- Enhance AI accuracy with larger datasets
- Integrate with governmental and NGO systems
- Deploy pilot program in a real-world environment

---

## Note
This project is currently under development and will be continuously updated with additional features, documentation, and implementation details.
