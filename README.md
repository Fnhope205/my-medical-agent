 🩺 My Medical Agent

An AI-powered medical assistant Telegram bot built with n8n Cloud and the OpenAI API.

 Overview

My Medical Agent is an educational automation project that connects Telegram messages to an AI-powered workflow. It receives user messages, processes them with an AI agent, and sends the generated response back through Telegram.

 Workflow

1. **Telegram Trigger** — Receives incoming Telegram messages.
2. **AI Agent** — Processes the message using the configured instructions.
3. **OpenAI Chat Model** — Generates an AI response using `gpt-5-mini`.
4. **Telegram Response** — Sends the response back to the user.

 Tech Stack

- n8n Cloud
- Telegram Bot API
- OpenAI API
- JSON workflow export

 Project Structure

```text
my-medical-agent/
├── workflow.json
├── README.md
└── screenshots/
```

 Setup

1. Download `workflow.json` from this repository.
2. Import it into your n8n instance.
3. Configure your own Telegram credentials.
4. Configure your OpenAI API credentials.
5. Review the workflow and test it with sample messages before activation.

 Security

- Never publish API keys or Telegram bot tokens.
- Configure credentials securely in n8n.
- Do not commit private user messages or medical records.
- Test with synthetic data rather than real patient information.

 Medical Disclaimer

This project is for educational purposes only. It does not replace professional medical advice, diagnosis, or treatment. AI-generated responses may be inaccurate.

 Author

 Created as a personal AI automation project using n8n.

Created as a personal AI automation project using n8n.
