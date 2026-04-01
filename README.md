# AI Receptionist Automation System

## 🚀 Overview
An AI-powered automation system built using n8n to handle customer inquiries, extract structured data, and trigger automated workflows.

## 🛠 Tech Stack
- n8n (workflow automation)
- OpenAI API
- Gmail API
- Google Sheets API
- Webhooks

## ⚙️ Features
- Reads inbound customer messages
- Uses AI to extract key data (party size, date/time)
- Sends automated responses
- Logs structured data into Google Sheets

## 🔌 How It Works
1. Incoming message is captured via Gmail/Webhook
2. Sent to OpenAI for processing
3. Extracted data is structured
4. Response is generated and sent
5. Data is stored in Google Sheets

## 📁 Files
- workflow.json → n8n workflow export
