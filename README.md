# MRT Agent 🤖

The **MRT Agent** (Modular Reasoning & Task Agent) is an AI-powered personal assistant built using n8n and OpenAI.  
It brings together multiple specialized sub-agents to handle your daily workflows with ease.

---

## 🚀 Features

- **Trello Agent** – Create, move, and delete Trello cards and lists seamlessly  
- **Google Calendar Agent** – Schedule, update, and delete meetings  
- **Gmail Agent** – Send, organize, and manage emails  
- **Notion Agent** – Update databases, create pages, and sync notes  
- **Google Tasks Agent** – Add, complete, and organize tasks  
- **Parent MRT Agent** – Coordinates all sub-agents for smooth task orchestration  

---

## 🧠 Architecture

Each agent is represented by a modular **JSON file** built in [n8n](https://n8n.io/), enabling easy migration, customization, and scaling.

```plaintext
agents/
│
├── mrt_agent.json
├── trello_agent.json
├── gmail_agent.json
├── notion_agent.json
├── google_calendar_agent.json
└── google_tasks_agent.json
```plaintext

---

## 💬 Try the Bot

You can test the live MRT agent directly on Telegram here (:  
👉 (https://t.me/mrtvg_bot)

---

## ⚙️ Setup

1. Import the JSON files into your n8n workspace.  
2. Configure API keys for:
   - Trello  
   - Google Calendar  
   - Gmail  
   - Notion  
3. Run the main **MRT Agent** workflow to connect all modules.

---

## 📈 Future Scope

- Integrate Slack, WhatsApp, and Google Drive  
- Add task prioritization and scheduling optimization  
- Expand multi-agent coordination logic  

---

## 📄 License

Released under the [MIT License](LICENSE).

---

## 🤝 Contributing

If you'd like to collaborate or explore custom AI automations, reach out at  
📧 vibhorgautam907@gmail.com
