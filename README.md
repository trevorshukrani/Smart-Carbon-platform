# Smart-Carbon-platform
SmartCarbon is a data-driven platform that tracks, analyzes, and reduces transport emissions using WhatsApp input, OCR receipt scanning, and real-time dashboards.
---

## 🚨 Problem Statement

Transport emissions in Kenya are poorly tracked due to:

- Inconsistent or missing data capture  
- Complex and expensive carbon accounting tools  
- Lack of accountability and emission benchmarks  

As a result, institutions cannot effectively measure or reduce their carbon footprint.

---

## 💡 Solution Overview

SmartCarbon is a three-layer platform that transforms raw transport data into actionable emissions intelligence:

1. **WhatsApp Carbon Tracker** – simple data entry via chatbot  
2. **OCR Receipt Scanner** – automated fuel data extraction  
3. **Carbon Dashboard** – real-time analytics and reporting  

---

## ⚙️ Key Features

- 📱 WhatsApp-based data input (no app required)  
- 📷 OCR fuel receipt scanning  
- 📊 Interactive emissions dashboard  
- 📉 Carbon budgeting and alerts  
- 🔐 Tamper-proof audit trail (cryptographic chain)  
- 📑 EPRA-ready reporting system  

---

## 🏗️ System Architecture

SmartCarbon follows a modular architecture:

- **Frontend:** React Dashboard / HTML UI  
- **Backend:** Node.js / Python API  
- **Database:** PostgreSQL / MongoDB  
- **OCR Engine:** Tesseract OCR  
- **Input Layer:** WhatsApp API  

---

## 🔄 How It Works

1. **Data Collection**  
   - Users submit trip data via WhatsApp  
   - Fuel receipts are scanned via OCR  

2. **Emission Calculation**  
   - Uses IPCC Tier 1 emission factors  

3. **Data Integration**  
   - Stored in structured database  

4. **Budget Allocation**  
   - Departments assigned emission limits  

5. **Monitoring**  
   - Dashboard tracks performance  

6. **Audit & Verification**  
   - Blockchain-style hash chain ensures data integrity  

---

## 📊 Dashboard Modules

- Emissions Overview  
- WhatsApp Tracker  
- OCR Scanner  
- Carbon Budgets  
- Manual Logs  
- Audit Trail  
- Reports Generator  

---

## 📦 Outputs

- CO₂ emission calculations  
- Department-level reports  
- Budget vs actual comparisons  
- Emission trend analytics  
- Verified audit certificates  

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/smartcarbon-platform.git

# Navigate into the project
cd smartcarbon-platform

# Install dependencies
npm install
# OR
pip install -r requirements.txt

# Run the application
npm start
# OR
python app.py
