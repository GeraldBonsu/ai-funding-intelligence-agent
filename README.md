# AI Funding Intelligence Agent

An automated AI system that discovers, filters, and tracks funding opportunities for startups, investment firms, and social enterprises.

## 🚀 Overview

This project uses AI and automation to:

- Search for funding opportunities across the UK, Ghana, and global sources
- Structure results into clean, usable data
- Deduplicate opportunities against a live database
- Store them in Google Sheets
- Send a weekly email summary of the most relevant opportunities

## 🧠 Tech Stack

- n8n (workflow automation)
- OpenAI (structured AI outputs)
- Tavily API (web search)
- Google Sheets API (database)
- Gmail API (notifications)

## ⚙️ How It Works

1. Weekly schedule trigger (Monday 9am)
2. AI agent searches for funding opportunities
3. Data is structured into JSON format
4. Opportunities are split into individual items
5. Existing opportunities are fetched from Google Sheets
6. Deduplication logic removes duplicates
7. New opportunities are appended to the sheet
8. A summary email is generated and sent

## 🧩 Workflow

The full workflow is available here:
/workflow/funding-intelligence-agent.json
