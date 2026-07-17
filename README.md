# Chatbot-IASTECH

![Typebot](https://img.shields.io/badge/Typebot-Workflow-blue)
![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Pipedrive](https://img.shields.io/badge/Pipedrive-CRM-green)
![WordPress](https://img.shields.io/badge/WordPress-Integration-21759B)
![License](https://img.shields.io/badge/License-MIT-yellow)

An intelligent chatbot solution that automates lead capture, qualification, and CRM management through an integrated workflow.

This project combines **Typebot**, **n8n**, **Pipedrive**, and **WordPress** to deliver a seamless experience from the first user interaction to automated lead qualification and CRM registration.

> **Note:** The workflows included in this repository are templates. All credentials, API keys, and environment-specific configurations have been removed.

---

## Features

- Interactive conversational interface built with Typebot
- Automated lead qualification
- Contact lookup in Pipedrive
- Automatic creation of People, Organizations, and Leads
- Workflow automation using n8n
- Conditional conversation flows
- REST API integrations
- WordPress website integration

---

## Architecture

```text
Visitor
    │
    ▼
WordPress Website
    │
    ▼
Typebot
    │
    ▼
n8n
 ├── Validate user data
 ├── Search existing contacts
 ├── Create or Update Person
 ├── Create Organization (Optional)
 └── Create Lead
    │
    ▼
Pipedrive CRM
```

---

## Technology Stack

- Typebot
- n8n
- Pipedrive API
- WordPress
- JavaScript
- HTML
- CSS

---

## Workflow

1. A visitor starts a conversation through the chatbot embedded on a WordPress website.
2. Typebot collects the required information.
3. The collected data is sent to an n8n workflow.
4. n8n validates and processes the submitted information.
5. Existing contacts are searched in Pipedrive.
6. If necessary, a new Person and Organization are created.
7. A qualified Lead is automatically created in the CRM.

---

## Project Structure

```text
.
├── workflows/
│   ├── typebot/
│   └── n8n/
│
├── workflow-images/
│   ├── typebot/
│   └── n8n/
│
└── README.md
```

---

## Key Benefits

- Automates lead acquisition
- Eliminates manual CRM data entry
- Standardizes the lead qualification process
- Improves CRM data consistency
- Provides a scalable and reusable automation workflow

---

## Disclaimer

This repository is intended for educational and demonstration purposes. Before using it in production, configure your own credentials, endpoints, and environment variables according to your infrastructure.
