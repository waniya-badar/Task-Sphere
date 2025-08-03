# Task-Sphere
Task Sphere - An intelligent AI assistant built with n8n that serves as your personal scheduler, task manager, and productivity strategist all in a single automated system. By combining LLM-powered understanding with workflow automation, Task Sphere organizes your meetings, tasks, and priorities without you lifting a finger.

### What It Can Do for You:
- Smart Scheduling – Automatically create and manage meetings/events
- Intelligent Task Assignment – Assign tasks to yourself with priority levels
- Sync Across Tools – Keep Google Sheets and Google Calendar in perfect sync
- Daily Briefings – Hear or read your schedule for the day
- Pending Task Summaries – Instantly summarize open items from Google Sheets
- Voice or Text Commands – Add tasks/events simply by speaking or typing
- Hands-Free Operation – Entirely powered by n8n automation flows

### How It Works:
- Trigger – Accepts a voice or text prompt (e.g., “Schedule project review for Friday at 10 AM”)
- AI Understanding – LLaMA/GPT interprets the request
- Workflow Routing – n8n directs the request to the right action:
  1. Google Calendar → Create/update events
  2. Google Sheets → Add or update tasks with priorities
- Response – Confirms the action or provides a full schedule/task summary
- Optional Notifications – Sends updates via Email, WhatsApp, Slack, etc.

### Tech Stack:
- n8n – Workflow automation framework
- LLM (LLaMA / GPT / Claude) – Intent recognition & conversation flow
- Google Calendar API – Meeting & event scheduling
- Google Sheets API – Task tracking & status management

Webhooks & n8n UI – Command input and results delivery

Optional Frontend – Streamlit, Telegram Bot, or voice assistant
