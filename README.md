
# 🤖 Conversational Chatbot with Flowise AI

This project is a **Conversational AI Chatbot** built using [Flowise AI](https://flowiseai.com/) that leverages **Google Gemini** for natural language understanding and **Upstash Redis** for long-term conversation memory. It is designed to handle friendly, context-aware, and detailed conversations with persistent memory across sessions.

---
<img width="1366" height="629" alt="Image" src="https://github.com/user-attachments/assets/55da4076-64f7-4fc4-b95e-64c2f9f0055d" />
<img width="1366" height="615" alt="Image" src="https://github.com/user-attachments/assets/1ad58293-e1d7-49a3-9f41-c0581f4f5690" />


## 📌 Features

- **Google Gemini LLM Integration** – Uses the latest `gemini-2.0-flash` model for high-speed, accurate responses.
- **Persistent Chat Memory** – Stores conversation history using **Upstash Redis**, enabling context continuity between interactions.
- **Customizable System Prompt** – Set your own tone and behavior for the chatbot.
- **Streaming Responses** – Supports real-time token streaming for faster user feedback.
- **Safety Filters** – Optional Google safety settings to filter harmful or unsafe content.
- **Flowise AI Node-based Workflow** – Easily configurable, visual chatbot logic.

---

## 🛠 Tech Stack

- **Flowise AI**
- **Google Gemini API**
- **Upstash Redis**
- **LangChain**
- **Node.js**

---

## 🚀 Getting Started

### 1️⃣ Prerequisites

Before starting, make sure you have:
- **Node.js** v18+
- **Flowise AI** installed
- A **Google Gemini API Key**
- An **Upstash Redis Database**

### 2️⃣ Installation

```bash
git clone https://github.com/yourusername/flowise-conversational-chatbot.git
cd flowise-conversational-chatbot
npm install -g flowise
npx flowise start
```

### 3️⃣ Import Chatflow

1. Open Flowise dashboard.
2. Import `Conversational Chatbot Chatflow.json`.
3. Set API keys and Upstash credentials.

### 4️⃣ Environment Variables

```
GOOGLE_API_KEY=your_google_gemini_api_key
UPSTASH_REDIS_REST_URL=https://your-upstash-url.upstash.io
UPSTASH_REDIS_REST_TOKEN=your_upstash_token
```

---

## 📂 Project Structure

```
.
├── Conversational Chatbot Chatflow.json
├── README.md
```

---

## 🧩 How It Works

1. **ChatGoogleGenerativeAI Node** – Connects to Google Gemini API.
2. **Upstash Redis-Backed Chat Memory Node** – Stores and retrieves chat memory.
3. **Conversation Chain Node** – Manages chatbot logic.

---

## 🖥 Usage

- Start chatbot in Flowise.
- Interact in Playground or embed in website.
- Persistent context awareness.

---

## 🔮 Future Enhancements

- Image input support.
- Custom knowledge base.
- Public API deployment.

---

## 📜 License

MIT License
