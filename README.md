# 🏥 Rural Healthcare AI Bot  
**AI-Powered Conversational Healthcare Solution for Rural India**

---

## 🧩 1. Problem Statement  
According to the **Health Dynamics of India Report** released by the **Ministry of Health and Family Welfare**, there is an **80% shortfall in community health centres (CHCs)** across rural India.  
Tier 2 and Tier 3 towns face limited healthcare access, doctor shortages, and poor infrastructure — forcing patients to travel long distances even for basic consultations.

At the same time, **mobile internet usage is growing rapidly** in rural India, with **425+ million smartphone users (as of January 2023)**.  

👉 This gap between healthcare access and mobile connectivity presents a major opportunity to deliver **AI-based digital healthcare support** to rural citizens.

---

## 💡 2. Objective  
Design and deploy an **AI-powered conversational healthcare assistant** that:

- 🩹 Provides verified first-aid and symptom-based guidance  
- 🧠 Helps users self-assess conditions and decide next steps *(self-care, consult doctor, or emergency)*  
- 🌐 Works in multiple Indian languages and low-bandwidth environments  
- ⚙️ Operates autonomously 24×7 via WhatsApp or other chat platforms  

---

## ⚙️ 3. Solution Overview  
The **Rural Healthcare AI Bot** is an intelligent chat-based healthcare system built using **n8n Cloud Automation**, **Google Gemini AI**, **Google Sheets**, and **WhatsApp API**.  

Users can describe their symptoms naturally (e.g., “I have fever and cold since morning”), and the bot instantly provides:  

- 🤖 AI-based health analysis  
- 🩺 Next-step recommendation  
- 👨‍⚕️ Doctor/hospital contact details (if consultation is required)  
- 🚨 Emergency alerts in critical cases  

---

## 🔁 Workflow Summary  

### 1️⃣ User Message (WhatsApp Input)
User sends a message like:  
> “I have fever and cold since morning.”

### 2️⃣ Language Detection & Translation  
Gemini AI auto-detects and translates messages to English (supports Indian regional languages).

### 3️⃣ AI Symptom Analysis  
Gemini classifies input into one of three categories:
- 🩹 **Self-care**
- 🧑‍⚕️ **Consult Doctor**
- 🚨 **Emergency**

### 4️⃣ Switch Logic in n8n  
Based on classification, the system routes the workflow accordingly.

### 5️⃣ Response Generation  
- **Self-care:** Provides first-aid or home remedies  
- **Consult Doctor:** Fetches relevant doctor/hospital info from Google Sheets  
- **Emergency:** Sends immediate hospital advice and nearby emergency contact  

### 6️⃣ Message Delivery  
Response is sent back via WhatsApp in the **user’s original language**, ensuring:
- Accurate, friendly, and reliable advice  
- Quick doctor contact info  
- Emergency instructions  

---

## 🧠 4. Technology Stack  

| Component | Tool / Platform | Purpose |
|------------|----------------|----------|
| **Automation Platform** | n8n Cloud | Workflow orchestration |
| **AI Model** | Google Gemini | Symptom analysis & language processing |
| **Messaging Interface** | WhatsApp Cloud API | Chat-based user interaction |
| **Data Source** | Google Sheets | Doctor & hospital database |
| **Logic Layer** | JavaScript Nodes | Case classification & routing |
| **Hosting** | n8n Cloud (Server Mode) | 24×7 autonomous operation |

---

## 📊 5. Workflow Architecture  
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/a0d85f33-9407-449e-900f-1ee2431f8c06" />


---

## 🌟 6. Unique Selling Points (USP)

- 🧠 **AI-Powered Multi-Language Assistant** — Understands English and Indian regional languages  
- 💬 **WhatsApp Integration** — Accessible via India’s most-used messaging platform  
- ⚙️ **Fully Automated 24×7 Cloud Workflow** — Hosted and managed on n8n Cloud  
- 🩺 **Smart Symptom Triage** — AI automatically classifies each case  
- 🌐 **Lightweight and Reliable** — Functions in low-connectivity zones  

---

## 🌍 7. Impact  

- 🏥 **Reduces load** on rural health centers by filtering self-care cases  
- 🕒 **Saves time** by avoiding unnecessary travel for basic consultations  
- 🌍 **Promotes inclusivity** — provides guidance in the user’s own language  
- 🚨 **Faster emergency identification** and timely alerts  
- 🤝 **Bridges the urban-rural healthcare gap**

---

## 🎯 8. Conclusion  
The **Rural Healthcare AI Bot** leverages **AI and automation** to bridge the healthcare access gap in rural India.  
It empowers citizens with **instant, safe, and reliable** health guidance through chat — reducing delays in care and improving public health awareness.

> 💬 “AI doesn’t replace doctors — it helps patients reach the right care faster.”

---

### 👥 Project Contributors
**Team Codecrafters**  
- Goutham Vaishnav *(Team Lead)*  
- Mohammed haji
- Ganireddy Umesh
- Piyush Suthar
- Manoj Chilukuri
---

### 📫 Contact
For queries or collaborations, please reach out at:  
📧 [gouthamvaishnav8@gmail.com]  
🎥 **[Click here to view the demo](https://drive.google.com/file/d/1d2rkiHQsIJyXmX_A63x6EjNaoPDhHV28/view?usp=drive_link)**  

<img width="600" height="600" alt="Screenshot 2025-10-08 181657" src="https://github.com/user-attachments/assets/3416f552-746d-41f4-9837-2a840e641436" />

---
<img width="1000" height="745" alt="Screenshot 2025-10-08 181725" src="https://github.com/user-attachments/assets/b3850db4-43e1-4518-8686-9ff9eea701d3" />

---

<img width="1000" height="910" alt="Screenshot 2025-10-08 181801" src="https://github.com/user-attachments/assets/ac42d5ae-d7af-46f1-b1e9-39d3d53ab89a" />

---

<img width="1000" height="542" alt="Screenshot 2025-10-08 181851" src="https://github.com/user-attachments/assets/d196c95a-629d-4a97-a843-4025702772c1" />

