# AI Email Drafting Assistant

An AI-powered email drafting application built with Python, Streamlit, and the OpenAI API.

## Overview

This project demonstrates how generative AI can help users compose professional emails quickly and efficiently.

The assistant generates email drafts based on user-provided instructions, reducing repetitive writing and improving productivity.

## Features

- AI-generated email drafts
- Simple, interactive Streamlit interface
- Professional email composition
- OpenAI API integration
- Secure API key configuration using environment variables

## Technology Stack

- Python
- Streamlit
- OpenAI API
- python-dotenv
- Git and GitHub

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/email-drafting-agent.git
cd email-drafting-agent
```

**2. Create a virtual environment**

```bash
python -m venv .venv
```

**3. Activate the environment (Windows PowerShell)**

```powershell
.\.venv\Scripts\Activate.ps1
```

**4. Install dependencies**

```bash
pip install -r requirements.txt
```

**5. Configure your API key**

Create a `.env` file and add:

```env
OPENAI_API_KEY=your_api_key_here
```

**6. Launch the application**

```bash
streamlit run app.py
```

Replace `app.py` with your actual Streamlit entry-point filename if different.

## Security

API credentials are stored in environment variables and excluded from version control. Never commit API keys or other sensitive information.

## Future Enhancements

- Gmail and Outlook integration
- Automated email classification
- AI-powered response suggestions
- Human approval before sending emails
- Agentic AI workflows for routine email management

## Project Purpose

A hands-on project exploring practical applications of generative AI, workflow automation, and intelligent assistants.

## Author

Charles Akl

Site Reliability Engineering | Automation | AI Enablement | Production Resilience