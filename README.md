# 🏬 Adidas AI WhatsApp Customer Support Bot

An AI-powered WhatsApp customer support automation built with **n8n** that handles FAQs, order tracking, product availability, and support ticket creation using Large Language Models and backend integrations.

This project demonstrates how conversational AI can be orchestrated with low-code automation tools to deliver real-time, scalable customer service.

---

## 🚀 Features

- WhatsApp-based customer interaction via Twilio  
- AI-powered responses using LLM (Groq)  
- Automated FAQ handling (returns, shipping, store hours, etc.)  
- Order tracking using Airtable database  
- Product and inventory lookup  
- Automatic support ticket creation and escalation  
- 24/7 automated customer assistance  
- Clean, human-like conversational flow  

---

## 🧠 System Architecture

User → WhatsApp → Twilio → n8n Webhook → AI Agent → Tools (Airtable) → Twilio → User  

---

## 🛠 Tech Stack

- n8n (Workflow Automation)  
- Twilio WhatsApp API  
- Groq LLM  
- LangChain Agent  
- Airtable  
- JavaScript (inside n8n expressions)


