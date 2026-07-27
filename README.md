# 🚀 S3 X Editorial Engine

An AI-powered editorial automation system that discovers AI news, researches topics, generates educational X (Twitter) threads, routes them through a human approval workflow, and publishes them automatically.

---

## 📖 Overview

S3 X Editorial Engine is an n8n-based automation pipeline built to eliminate the manual effort involved in consistently publishing high-quality educational content on X.

Instead of manually researching news, writing threads, and publishing posts, this system automates the entire editorial workflow while keeping a human-in-the-loop approval process before publication.

---

## 🎯 Problem

Publishing high-quality AI content consistently requires multiple repetitive steps:

- Discovering relevant AI news
- Filtering low-quality stories
- Researching selected topics
- Writing engaging educational threads
- Reviewing content before publishing
- Posting to X manually

This process is time-consuming and difficult to sustain consistently.

---

## 💡 Solution

The S3 X Editorial Engine automates the editorial pipeline by combining AI, workflow automation, and human approval.

The workflow:

1. Collects AI news
2. Selects the most relevant stories
3. Generates educational X threads using LLMs
4. Sends the draft to Telegram for approval
5. Publishes approved content automatically

This enables consistent, scalable content creation while maintaining editorial quality.

---

## ✨ Current Features

- RSS-based AI news ingestion
- AI-powered topic selection
- Automated research generation
- Educational X thread generation
- Telegram approval workflow
- Automatic publishing to X
- End-to-end workflow built using n8n

---

## 🏗️ Repository Structure

```
S3-X-Editorial-Engine/

├── workflows/
│   └── S3-X-Editorial-Engine-v1.0.0.json

├── README.md

├── LICENSE

└── .gitignore
```

---

## 🛠️ Tech Stack

- n8n
- OpenAI
- Telegram Bot API
- RSS Feeds
- X (Twitter) API

---

## 🗺️ Roadmap

- [ ] Multi-source news aggregation
- [ ] AI image generation
- [ ] Better editorial scoring
- [ ] Prompt versioning
- [ ] Multi-platform publishing
- [ ] Analytics dashboard

---

## 👤 Author

**Shubham Sawant**

Building AI systems at the intersection of AI, Economics, Markets and Automation.

Project under the **S3conomics.ai** initiative.