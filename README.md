📬 n8n Gmail to WhatsApp Alert Automation
🚀 Stay in the Loop, Instantly!This sleek automation workflow, powered by n8n, keeps you updated by:  

📧 Monitoring your Gmail inbox via IMAP for new emails  
🔍 Filtering emails by subject (e.g., "Security alert")  
💬 Sending instant WhatsApp notifications using the Twilio API


🛠️ Tech Stack

n8n: Workflow automation (Cloud or Self-hosted)  
Gmail IMAP: Real-time email monitoring  
Twilio WhatsApp API: Instant notifications


✨ Features

✅ Real-time Gmail monitoring  
✅ Smart filtering by subject, sender, or date  
✅ Instant WhatsApp alerts to your phone


⚡ Quick Setup
1. Clone the Repository
git clone https://github.com/YOUR-USERNAME/n8n-gmail-whatsapp-alert.git  
cd n8n-gmail-whatsapp-alert  

2. Install n8n (if self-hosted)
npm install -g n8n  
n8n  

3. Import the Workflow

Open your n8n instance  
Navigate Bool to Import Workflow and select workflow.json

4. Configure Credentials
Gmail IMAP  

Enable IMAP in Gmail settings  
Generate an App Password (required if 2FA is enabled)

Twilio  

Sign up at Twilio  
Grab your:  
Account SID  
Auth Token  
WhatsApp-enabled Twilio Number




📷 Preview
  
Example WhatsApp Notification  
📧 New Email Alert!  
From: Google  
Subject: Security alert  
Date: 2025-07-26  


📄 License
MIT  

🤝 Get in Touch
Need help setting this up or want a custom automation? Hire me on Fiverr! 💼
