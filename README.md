# n8n Telegram AI Agent – Inventory + Email Automation

This project is an end-to-end automation built using **n8n**, combining:
- AI Agent (LLM)
- Telegram Bot
- Google Sheets Inventory Database
- Gmail Email Automation

The workflow allows users to:
- Chat with a Telegram bot
- Retrieve inventory data from Google Sheets
- Automatically send emails containing inventory data in HTML format
- Generate dynamic email subjects and content using the AI Agent

---

## 🚀 Features

### 🤖 AI Chat Agent
- Responds intelligently to users
- Understands natural language
- Decides when to call tools (Google Sheets, Gmail)

### 📊 Google Sheets Integration
- Fetches real inventory data
- Data automatically formatted into HTML tables
- No spreadsheet ID or range required inside the chat

### 📩 Gmail Automation
- Sends emails automatically
- AI generates subject + HTML email body
- User only provides the recipient email

### 💬 Telegram Bot
- Easy interaction for end users
- Messages trigger the n8n workflow instantly

---

## 🛠️ Tools & Technologies Used

| Tool / Service | Purpose |
|----------------|---------|
| **n8n** | Automation workflow engine |
| **Telegram Bot API** | Chatbot communication |
| **Google Sheets** | Inventory database |
| **Gmail API** | Sending emails |
| **AI Agent (LLM)** | Natural language understanding and tool triggering |

---

## 📁 Folder Structure

