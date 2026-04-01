# AI Receptionist & Lead Intake Automation System

## 🚀 Overview
A multi-workflow automation system built using n8n to handle customer communication, lead intake, and follow-up processes.

This system automates SMS conversations, responds to missed calls, and uses AI to extract structured data from customer messages.

---

## 🛠 Tech Stack
- n8n (workflow automation)
- JavaScript (code nodes)
- OpenAI API
- Twilio API (SMS & Voice)
- Google Sheets API
- Webhooks

---

## ⚙️ Core Features

### 📩 SMS Lead Intake
- Captures customer inquiries via SMS
- Guides users through structured questions (service, location, timeline)
- Stores conversation state across messages
- Supports opt-in / opt-out (STOP/START)

### 🤖 AI-Powered Message Processing
- Uses OpenAI to interpret natural language messages
- Extracts structured lead data automatically
- Answers common business questions

### 📞 Missed Call Text-Back
- Detects missed calls
- Sends automated follow-up SMS
- Returns voice response via TwiML
- Logs call events for follow-up

### 📊 Data Logging & Tracking
- Stores leads and message history in Google Sheets
- Enables internal tracking and follow-up workflows

---

## 🔌 System Architecture

1. Incoming message or call triggers webhook
2. Workflow processes input (SMS or voice)
3. OpenAI extracts structured data (if applicable)
4. System sends automated response
5. Data is logged into Google Sheets

---

## 📁 Files

- `AI Receptionist V1 (SMS).json` → SMS intake workflow  
- `AI Receptionist V2 (AI Text).json` → AI-powered message processing  
- `Missed Call Text Back (SMS).json` → Missed call automation  

---

## 💡 Use Case

Designed for service-based businesses to automate customer intake, reduce manual communication, and capture leads efficiently.
