# 🤖 AI Meeting-to-Proposal Automation
> **Transforming transcripts into professional business assets in seconds.**

This is a high-level **n8n workflow** designed for consultants and agencies. It bridges the gap between a sales call and a professional proposal by leveraging AI.

## 🌟 Key Features
- **Fireflies Integration:** Automatically pulls meeting transcripts.
- **AI Reasoning:** Uses **Gemini 1.5 Pro** to act as a Senior AI Solutions Consultant.
- **Proposal Generation:** Creates a structured, high-converting business proposal.
- **Gamma Presentation:** Automatically generates a 10-slide presentation deck via API.
- **Human-in-the-loop:** Slack notifications for approval before the final deck is built.

## 🛠️ Tech Stack
- **Automation:** [n8n.io](https://n8n.io/)
- **Intelligence:** Gemini (via OpenRouter)
- **Transcription:** Fireflies.ai
- **Output:** Gamma.app, Google Sheets, Slack

## 🚀 How to Setup
1. **Import:** Download the `meeting-to-proposal.json` file and import it into your n8n.
2. **Credentials:** Set up your API keys for Fireflies, OpenRouter, Gamma, and Slack.
3. **Configure:** Update the Google Sheet ID and Slack Channel ID to match your environment.

---
*Created by **Yanis** - AI Automation & Mechanical Engineer*
