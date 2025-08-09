# jobs-Notifier-Workflow
Automate AI/ML job alerts with this n8n workflow! It fetches remote software development jobs, filters for AI/ML roles, summarizes descriptions using Hugging Face, sends email notifications, and logs details in Notion. Easy to set up and customize for your job search needs.


##Here How You can run this by importing .json file in n8n

---

## Features
- Fetches latest remote software dev jobs from Remotive API
- Filters for AI, Machine Learning, NLP, Data Scientist roles
- Summarizes job descriptions with Hugging Face NLP model
- Sends personalized email alerts
- Logs jobs to a Notion database for tracking

---

## How to Import Workflow into n8n
Download the workflow JSON
Download the workflow.json file from this repository.
2. Open your n8n instance (local or cloud).
3. In the n8n editor, click on the menu → **Import from File**.
4. Select the `.json` file from this repo.
5. The workflow will load with all nodes and settings configured.

---

## Setting up Notion Integration

1. Create a Notion integration at [Notion Developers](https://www.notion.so/my-integrations).
2. Share your job tracking database page with this integration (invite by integration email).
3. Copy the database ID from your Notion database URL.
4. In n8n, add your Notion API credentials.
5. Update the Notion node with your database ID to enable job logging.

---

## SMTP Email Setup

1. Use your Gmail or any SMTP-enabled email account.
2. Create an app password (for Gmail, enable 2FA and generate app password).
3. Add SMTP credentials in n8n credentials manager.
4. Emails will be sent to your specified recipient with job details.

---

## Improvements and Next Steps

- Add LinkedIn job scraping for more comprehensive listings.
- Improve email personalization with user preferences.
- Create a simple frontend dashboard to view and manage jobs.
- Expand to support multiple job categories and locations.

---

## License

MIT License

---

Feel free to customize and contribute!

