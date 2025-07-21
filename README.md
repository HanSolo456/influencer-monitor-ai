# 🔍 Spyfluence Automation Website

Spyfluence is an AI-powered influencer monitoring platform that automatically tracks influencers on YouTube and delivers instant video summaries via WhatsApp and Discord.

This lightweight web app is designed to:
- Accept a YouTube channel link or handle from the user
- Trigger an N8N webhook that:
  - Fetches the latest video
  - Summarizes its content using ChatGPT
  - Sends the summary to WhatsApp and Discord

## 🌐 Live Demo

> Coming soon on Netlify...

## 🚀 Features

- Accepts full YouTube Channel URL or @handle
- Automatically extracts valid `channelId`
- Triggers backend workflow hosted in [n8n](https://n8n.io/)
- Sends AI-generated summary to WhatsApp and Discord via webhooks

## 🛠️ Built With

- HTML5 + CSS3
- Vanilla JavaScript
- n8n (Automation backend)
- OpenAI (ChatGPT for summarization)
- WhatsApp Cloud API & Discord Webhooks
