# n8n-automation-projects
A collection of AI-powered automation workflows built with n8n, showcasing practical business process automation using AI agents, APIs, and no-code tooling.
## Projects
### Intake Funnel
Captures lead submissions via a webhook, processes the incoming data, and automatically sends a confirmation email through Gmail.
### Automated Archivist
Monitors a Gmail inbox for incoming invoices, uses Google Gemini AI to analyze and extract data from PDF attachments, archives the file to Google Drive, and logs the extracted data to Google Sheets.
### Lead Qualifier (Part 1)
A rule-based lead routing system. Validates incoming form submissions, checks budget tier, and routes leads accordingly — standard leads are logged to a spreadsheet with an auto-reply, while high-value leads trigger a Slack alert to the sales team.
### Lead Qualifier (Part 2 — AI Agent)
An evolution of the lead qualifier that replaces fixed rules with a Google Gemini-powered AI agent. The agent has access to three tools (log to spreadsheet, message the lead, alert sales on Slack) and decides which actions to take based on the lead's data.
### E-Commerce FX Engine
Automatically keeps product prices in sync with live currency exchange rates. On a schedule, the workflow fetches the current USD to NGN exchange rate, then loops through every product in the database and updates the local-currency price accordingly — no manual recalculation needed when rates shift. Built in two versions: one using Airtable, one using Google Sheets, as the data backend.
### Tools & Technologies
n8n — workflow automation platform
Google Gemini API — AI-powered document analysis and agent reasoning
Google Workspace — Gmail, Sheets, Drive
Airtable — structured data storage and automation
Slack API — team notifications
Telegram Bot API — messaging integration
### About
A practical exploration of automation patterns — from simple rule-based workflows to AI agents capable of making their own decisions. Each project solves a real operational problem: lead routing, document processing, and automated notifications.
