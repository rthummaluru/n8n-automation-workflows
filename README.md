# ⚙️ n8n Automation Workflows

This repository contains a collection of my n8n workflows — built to automate tasks across APIs, productivity tools, databases, and AI integrations.

---

## 📂 Folder Structure

```
.
├── README.md
├── workflows/
│   ├── job-application-followup.json
│   ├── notion-ai-summarizer.json
│   ├── github-issue-notifier.json
│   └── slack-alerts-on-error.json
└── images/
    └── workflow-overview.png (optional screenshots)
```

---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/n8n-workflows.git
   cd n8n-workflows
   ```

2. Open [n8n](https://n8n.io/) (cloud or self-hosted)

3. In the editor UI:
   - Click **"Import Workflow"**
   - Select any `.json` file from the `/workflows` directory

4. Configure any required:
   - API credentials (Airtable, Gmail, Slack, Notion, etc.)
   - Environment variables or node parameters

---

## 📌 Workflows Overview

| File                              | Description                                          | Trigger Type   | Status        |
|-----------------------------------|------------------------------------------------------|----------------|---------------|
| `job-application-followup.json`   | Sends automated follow-up emails via Airtable        | Schedule       | ✅ Working     |
| `notion-ai-summarizer.json`       | Summarizes new Notion pages using GPT                | Webhook        | ✅ Working     |
| `github-issue-notifier.json`      | Notifies Slack on new GitHub issues                  | Polling API    | 🔧 In Progress |
| `slack-alerts-on-error.json`      | Monitors workflows and sends Slack error alerts      | Internal Hook  | ✅ Working     |

---

## 🔐 Authentication & Configuration

Each workflow may require connected credentials:

- Airtable
- Gmail / SMTP
- Notion
- GitHub
- Slack
- OpenAI

Be sure to configure these in your n8n credentials UI before executing workflows. Never commit API keys or secrets to the repository.

---

## 🧠 Why This Exists

These workflows aim to:

- Save time through automation
- Demonstrate low-code integrations with APIs and AI
- Serve as templates for rapid prototyping and experimentation

---

## 🚰 Requirements

- [n8n](https://n8n.io/) (cloud or local)
- Access to any 3rd party APIs used in the workflows
- Basic understanding of nodes, expressions, and credentials setup

---

## 📸 Screenshots (Optional)

You can include screenshots of each workflow canvas in the `/images` folder and link them here.

Example:

![Job Application Workflow](images/job-application-overview.png)

---

## 🧪 Future Improvements

- Add retry logic or error handling to long chains
- Convert static fields to dynamic variables
- Create subworkflows for reusable steps

---

## 🧑‍💻 Contributing

Feel free to fork, reuse, or submit PRs for improvements, new workflows, or bug fixes.

---

## 📄 License

MIT License. Use freely with credit.
