# 🧠 AI-Powered Personal Assistant with n8n

This is an advanced n8n workflow that acts like a personal assistant. It integrates email, calendar, web search (via Perplexity), and memory storage (via Zep) to perform various smart tasks.

---

## 📌 Features

- 📬 **Email Automation**
  - Send emails
  - Reply to received emails
  - Retrieve unread emails
  
- 📅 **Calendar Control**
  - Create, update, and delete Google Calendar events
  
- 🌐 **Web Search**
  - Search the web using Perplexity API
  
- 🧠 **Long-Term Memory**
  - Store and retrieve context using Zep (vector database)

---

## 🧩 Tech Stack

- [n8n](https://n8n.io/)
- Gmail API
- Google Calendar API
- Perplexity AI (via HTTP node)
- Zep Vector DB

---

## 🚀 How It Works

1. Triggers on your command or schedule
2. Uses natural language inputs to:
   - Fetch info from inbox or calendar
   - Perform search on web
   - Generate reply or schedule actions
3. Remembers context using Zep for future reference

---

## 📸 Demo & Screenshots

### ▶️ **Video Demo**  
[Watch on Loom](https://loom.com/your-video-link)

### 🖼️ **Screenshots**  
![Workflow Screenshot](./screenshots/workflow-view.png)  
*Entire workflow inside n8n*

![Email Response](./screenshots/email-reply.png)  
*Example of automatic email response*

---


