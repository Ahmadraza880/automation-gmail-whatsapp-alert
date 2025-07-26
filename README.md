📬 n8n Gmail to WhatsApp Alert Automation
This project is an automation workflow built using n8n that:

Listens for new emails from Gmail using IMAP
Filters for specific subjects (e.g., "Security alert")
Sends a notification to WhatsApp using Twilio API


⚙️ Tech Stack

n8n (Cloud or Self-hosted)
Gmail IMAP Integration
Twilio WhatsApp API


🚀 Features

✅ Triggers on incoming Gmail messages
✅ Filters messages by subject, sender, or date
✅ Sends real-time WhatsApp notifications to your number


🔧 Setup Instructions
1. Clone this Repository
git clone https://github.com/YOUR-USERNAME/n8n-gmail-whatsapp-alert.git
cd n8n-gmail-whatsapp-alert

2. Install n8n (if self-hosted)
npm install -g n8n
n8n

3. Import Workflow

Open n8n
Click on Import Workflow and select workflow.json

🛠️ Required Credentials
Gmail IMAP

Enable IMAP in Gmail settings
Create an App Password if 2FA is enabled

Twilio

Sign up at Twilio
Get your:
Account SID
Auth Token
WhatsApp-enabled Twilio Number




📷 Screenshot
<img width="810" height="400" alt="image" src="https://github.com/user-attachments/assets/908a44b0-3e49-4cf5-9035-259762a85214" />


📬 Example WhatsApp Message
📧 New Email Alert!
From: Google
Subject: Security alert
Date: 2025-07-26


📄 License
MIT

🤝 Let's Connect
Want help setting this up for your business? Contact me on Fiverr 💼
