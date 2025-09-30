# 🎬 AI Content Factory Workflow

This repository contains my **n8n automation workflow** for repurposing long-form YouTube videos into Shorts, generating titles & descriptions with AI, and publishing them automatically.  

## 🔧 Features
- ⏰ Scheduled trigger for workflow automation  
- 📑 Fetches long-form video data from Google Sheets  
- ✂️ Uses Klap API to clip videos into Shorts  
- 🤖 AI agents generate **YouTube titles & descriptions** using OpenAI  
- 📤 Publishes directly to YouTube with metadata  
- 📝 Logs results back into Google Sheets  

## 📂 Files
- `content_factory_workflow.json` → n8n workflow export (import directly into your n8n instance)  

## 🚀 How to Use
1. Clone this repo or download the JSON file  
2. In your n8n instance, go to **Import Workflow** → Upload the JSON  
3. Replace placeholders:
   - `SHEET_ID_PLACEHOLDER` → Your Google Sheet ID  
   - `CREDENTIAL_ID_PLACEHOLDER` → Your n8n credentials for Google, Klap, OpenAI, YouTube  
4. Activate the workflow and let it run 🎉  

## ⚠️ Notes
- Credentials are replaced with placeholders for security  
- You’ll need your own API keys for **Google Sheets, Klap API, OpenAI, and YouTube**  

---

💡 I’m sharing this as part of my **AI automation portfolio**.  
Follow me on [TikTok](https://tiktok.com/yourprofile), [YouTube](https://youtube.com/yourchannel), and [LinkedIn](https://linkedin.com/in/yourprofile) for tutorials and more projects.  
