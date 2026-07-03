# Chatbot-IASTECH

An intelligent chatbot solution designed to automate lead capture, qualification, and CRM management through an integrated workflow.

The project combines **Typebot**, **n8n**, **Pipedrive**, and **WordPress** to provide a seamless experience from the first user interaction to automated lead qualification and CRM integration.

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
3. n8n validates and processes the submitted data.
4. Existing contacts are searched in Pipedrive.
5. If necessary, a new Person and Organization are created.
6. A qualified Lead is automatically generated in the CRM.

---

## Objectives

- Automate lead acquisition
- Eliminate manual CRM data entry
- Standardize the lead qualification process
- Improve CRM data consistency
- Provide a scalable automation workflow
