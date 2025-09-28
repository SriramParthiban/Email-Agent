# Email-Agent

# 📧 Email Agent Demo (n8n + OpenAI + Gmail)

This repository contains an **n8n workflow** that transforms Gmail into an **AI-powered email assistant**.  
It uses **OpenAI** for natural language understanding and **n8n** automation to handle email tasks efficiently.

---

## 🚀 Features
- **AI-Powered Email Writing**  
  Generates professional, ready-to-send drafts with a polite and concise tone.

- **Inbox Management**  
  Retrieve, filter, and organize emails (e.g., fetch last 2 emails from a sender).

- **Smart Personalization**  
  Every email is structured with warmth and professionalism, signed off as:  



- **Workflow Automation**  
- Composes and replies to emails  
- Sends emails directly via Gmail  
- Fetches past messages for quick reference  
- Manages inbox with labeling, archiving, or marking as read  

---

## 🛠️ Tech Stack
- **[n8n](https://n8n.io/):** Workflow automation engine  
- **OpenAI GPT-4o-mini:** Language model for generating responses  
- **Gmail API:** Sending, retrieving, and managing emails  

---

## 📂 Workflow Overview
1. **Trigger:** Workflow starts when executed by another workflow.  
2. **AI Agent:** Interprets the user’s query with personality rules.  
3. **OpenAI Chat Model:** Produces structured, professional outputs.  
4. **Gmail Tool:** Executes tasks (send/retrieve emails).  
5. **Response Node:** Returns clean output to the user.  

---

## ⚡ Example Usage
- *"Compose a reply to John thanking him for his feedback."*  
- *"Grab my last 2 emails from Aron."*  
- *"Draft an email to HR about leave request."*  

---

## 📌 Notes
- No placeholders — all drafts are **ready-to-send**.  
- Prevents sending sensitive information without confirmation.  
- Professional, approachable, and well-structured communication.  

---

## 🤝 Credits
Developed by **Sriram Parthiban** using **n8n** and **OpenAI**.  

