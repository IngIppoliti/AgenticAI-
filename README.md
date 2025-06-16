# AgenticAI-
N8N agentic flows


# AI Job Application Agent (n8n + Perplexity + Gmail + Google Docs + Telegram + Notion)

🤖 Automate your job application process with AI-powered feedback, cover letters, and CV suggestions using n8n workflows and Perplexity API.

## 🔍 Use Case

Every time a new job offer is received via email:
1. The system analyzes the offer and extracts useful information.
2. It computes a **Match Grade** vs your CV.
3. It suggests **how to improve your CV**.
4. It generates a **tailored Cover Letter** using Perplexity.
5. Results are saved in Notion, emailed via Gmail, and notified through Telegram.

## 🧠 Tools & Stack

- [n8n](https://n8n.io/) – Workflow automation
- [Perplexity API](https://www.perplexity.ai/) – LLM-based reasoning
- Gmail / Google Docs / Telegram – Communication channels
- Notion – Tracking job applications
- Google Drive – CV management
- OCR.Space – Parsing job descriptions from screenshots
- AWS EC2 – Self-hosted n8n instance

## 🧭 Workflow Architecture

![Workflow Architecture](./agentic_ai_architecture.png)

## 📎 Example Output

![image](https://github.com/user-attachments/assets/0f981886-c9d1-415f-83f8-23fb8032c04f)


## 🧰 Setup

1. Clone this repo
2. Import the `.json` workflows into your n8n instance
3. Add environment variables for Perplexity, Gmail, Google Drive, Notion, Telegram
4. Adjust the prompts in `/prompts/` directory if needed

## 📽️ Demo (coming soon)

## 👨‍💼 Author

Daniele Ippoliti – IT Manager & AI Expert  
📧 ing.ippoliti@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/danieleippoliti)

---
