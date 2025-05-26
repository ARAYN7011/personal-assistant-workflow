# 🧠 AI-Powered WhatsApp Personal Assistant (n8n Workflow)

This is a powerful **n8n workflow** that acts as a personal assistant, triggered via WhatsApp. It automates tasks like replying to emails, managing calendar events, searching the web (via Perplexity), and storing long-term memory (via Zep).

---

## 📌 Features

- 💬 **WhatsApp Trigger**
  - Listens to messages on WhatsApp using webhook (e.g., 360dialog or Meta Cloud API)
  - Parses user input and initiates relevant actions

- 📬 **Email Automation**
  - Send emails
  - Reply to received emails
  - Retrieve unread messages

- 📅 **Calendar Integration**
  - Create, update, and delete events in Google Calendar

- 🌐 **Web Search**
  - Use Perplexity AI to search the web via HTTP node

- 🧠 **Long-Term Memory**
  - Store and recall context using Zep vector database

---

## 🧩 Tech Stack

- [n8n](https://n8n.io/)
- WhatsApp API (360dialog / Meta Cloud API / Twilio)
- Gmail API
- Google Calendar API
- Perplexity AI API
- Zep Vector DB

---

## 🚀 How It Works

1. WhatsApp message triggers the workflow (via webhook)
2. n8n interprets the command (e.g. "Check unread emails", "Create event", "Search news")
3. Executes the task and replies on WhatsApp
4. Stores the context or conversation with Zep

---

## 🔐 API Credentials Used

| Service       | Auth Type       | Where to Get Token / API Key                    |
|---------------|------------------|--------------------------------------------------|
| WhatsApp API  | Bearer Token     | From 360dialog or Meta Developer Portal         |
| Gmail         | OAuth2           | Google Cloud Console                            |
| Calendar API  | OAuth2           | Same as above                                   |
| Perplexity    | API Key (HTTP)   | [Perplexity API](https://docs.perplexity.ai)    |
| Zep           | API Key (HTTP)   | [Zep Docs](https://docs.getzep.com)             |

---

## 📸 Demo & Screenshots

### ▶️ **Video Demo**  
[Watch on Loom](https://loom.com/your-demo-link)

### 🖼️ **Screenshots**  
![image](https://github.com/user-attachments/assets/0c0b4754-bb6b-40e5-bff5-328db98f52e1)

![image](https://github.com/user-attachments/assets/b76208d7-902b-42b7-9d1d-8609d11805f9)

![image](https://github.com/user-attachments/assets/f9ce8140-c8ef-4997-ac82-c177009831dd)

![image](https://github.com/user-attachments/assets/2fd6ea47-405a-4701-be66-fa4c73b337da)


---

## 🗃️ Folder Structure

personal-assistant-workflow/
├── README.md
├── workflow.json
├── screenshots/
│ ├── workflow-overview.png
│ └── whatsapp-chat.png


---

## 📦 Installation

1. Clone this repo or download the `workflow.json`
2. Import into your n8n instance
3. Configure the following credentials:
   - WhatsApp API (360dialog / Meta)
   - Gmail
   - Google Calendar
   - Perplexity API
   - Zep API
4. Deploy your WhatsApp webhook URL using platforms like:
   - [Meta Cloud API](https://developers.facebook.com/docs/whatsapp/)

---

## 🙋‍♂️ Author

Built with ❤️ by Aryan Pasreja 

---

## 📣 License

Free to use and customize
