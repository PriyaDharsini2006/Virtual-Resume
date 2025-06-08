---
title: virtual_resume-1
app_file: app.py
sdk: gradio
sdk_version: 5.33.0
---
# virtual-resume-1

## Description
This project is a virtual resume chatbot built using Gradio and OpenRouter.  
It reads a PDF profile and a summary text to answer questions about the user's career, background, and skills.  
It also uses tools to record user details and unknown questions via Pushover notifications.

---

## Features

- Chatbot interface using Gradio
- Reads user profile from PDF and summary text files
- Uses OpenAI deepseek/deepseek-chat-v3-0324:free model via OpenRouter API
- Records user interest and unknown questions with Pushover notifications
- Dependency management with `uv`

---

## Requirements

- Python 3.10 or higher
- `uv` tool for environment and dependency management which is 10x-100x faster

---

## Environment Variables

Create a `.env` file in your project root with these keys:

```env
GROQ_API_KEY=
OPENROUTER_API_KEY=
GEMINI_API_KEY=
PUSHOVER_USER=u
PUSHOVER_TOKEN=


##  uv
Step 1: Install uv (if not installed)
# pip install uv
# uv venv
# uv add <package-name>
# uv sync

✅ When you add a package with uv add, it will automatically create pyproject.toml and uv.lock for you!

or install all packages at one go with the command 
# uv add -r requirements.txt  







