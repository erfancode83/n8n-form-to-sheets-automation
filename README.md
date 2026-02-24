# 🚀 Smart Form Automation with n8n

A robust, low-code automation workflow that connects **Google Forms** to **Google Sheets** with built-in logic for data integrity and professional communication.

## ✨ Key Features
- **Real-time Monitoring:** Automatically triggers every 60 seconds (Polled) when a new row is added.
- **Smart Validation:** Uses Regex to ensure only valid email formats are processed.
- **Error Handling:** Integrated `Stop and Error` logic to catch and log invalid submissions.
- **Professional Outreach:** Sends beautiful, responsive **HTML emails** with RTL support (Persian/Arabic friendly).
- **Update Logic:** Uses `Append or Update` to prevent duplicate entries based on email unique keys.

## 🛠️ Tech Stack
- **Automation:** [n8n.io](https://n8n.io/)
- **Storage:** Google Sheets API
- **Communication:** Gmail API
- **Logic:** JavaScript / Regex

## 📋 Workflow Visualization


## 🚀 How to Use
1. **Import the JSON:** Copy the provided JSON code in this repo and paste it into your n8n canvas.
2. **Credentials:** - Connect your **Google Sheets Trigger** account.
   - Connect your **Gmail OAuth2** account.
3. **Configure Sheet:** Update the `Document ID` to match your own Google Sheet.
4. **Activate:** Toggle the workflow to 'Active'.

## 📧 Email Template
The workflow includes a custom HTML/CSS template designed for high conversion:
- Clean, modern design.
- RTL Support.
- Mobile responsive.

---
*Developed with ❤️ by [Your Name]*
