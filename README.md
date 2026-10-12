# 🚗 Car Showroom Customer Support Agent — n8n AI Automation

An AI-powered customer support agent built with **n8n** that answers customer questions about a car showroom using Google Sheets as its FAQ knowledge base.

## 📌 Project Overview

This project automates customer support for a car showroom using an AI agent connected to Google Sheets. It helps customers get quick answers to frequently asked questions about the showroom, available vehicle categories, and new or used cars.

The goal is to reduce repetitive manual responses and provide customers with a smoother support experience.

## ✨ Features

- 🤖 **AI-Powered Customer Support** — Understands customer questions and generates natural-language responses.
- 📊 **Google Sheets Integration** — Retrieves showroom FAQs from a Google Sheets document.
- 💬 **Conversational Responses** — Provides friendly and helpful answers to customer queries.
- ⚡ **Workflow Automation** — Connects AI and data retrieval through an n8n workflow.
- 🛡️ **Reliable Responses** — Uses available FAQ information and avoids inventing unsupported details.

## 🛠️ Technologies Used

- **n8n** — Workflow automation
- **AI Agent** — Processes customer questions and generates responses
- **Google Gemini** — AI language model
- **Google Sheets** — Stores showroom FAQs and answers

## ⚙️ How It Works

1. **Customer sends a question** through the n8n chat interface.
2. **AI Agent receives the message** and understands the customer's intent.
3. **Google Sheets tool retrieves information** from the configured showroom FAQ sheet.
4. **AI generates a response** using the relevant information.
5. **Customer receives an answer** in a clear and conversational format.

## 🔄 Workflow Architecture

```text
Customer Question
       ↓
   Chat Trigger
       ↓
    AI Agent
       ↓
Google Gemini Chat Model
       ↓
Google Sheets FAQ Tool
       ↓
Relevant Information
       ↓
AI-Generated Response
       ↓
Customer
```

*Note: The AI Agent uses the connected Google Sheets tool to retrieve relevant information when needed.*

## 💡 Example Use Cases

Customers can ask questions such as:

- What cars do you sell?
- Do you sell new or used cars?
- What types of vehicles are available?
- Can you provide more information about a particular vehicle?

The agent uses the configured FAQ data to answer supported questions. Questions requiring live inventory, pricing, or vehicle-specific details need the appropriate data source to be connected.

## 🚀 Setup Instructions

### 1. Import the workflow
- Open your n8n instance.
- Import your exported workflow JSON file, if you are sharing one.

### 2. Configure Google Sheets
- Connect your Google Sheets account.
- Select your showroom spreadsheet and FAQ worksheet.
- Add your questions and answers in the appropriate columns.

### 3. Configure the AI model
- Connect your Google Gemini credentials.
- Select an available model in your n8n AI Agent workflow.

### 4. Test the workflow
- Open the chat interface.
- Ask a sample question, such as: `What cars do you sell?`
- Confirm that the agent retrieves relevant FAQ information and generates an appropriate response.

## 📁 Suggested Repository Structure

```text
car-showroom-customer-support-agent/
├── README.md
├── workflow/
│   └── car-showroom-agent.json
└── screenshots/
    └── workflow-overview.png
```

*The folders and files above are suggestions. Include them only if you create or export those assets.*

## 🔒 Security Notes

- Never upload API keys, passwords, access tokens, or private credentials.
- Remove sensitive information before sharing an exported n8n workflow.
- Use your own Google Sheets and AI credentials when importing the workflow.

## 🎯 Project Goal

To demonstrate how AI agents and workflow automation can improve customer support by connecting conversational AI with structured business data.

## 👨‍💻 Author

**Mujtaba Baig**  
BS Software Engineering Student  
Interested in AI Automation, AI Agents, and Workflow Development.

---

⭐ *This project is part of my hands-on learning journey in AI automation and intelligent business solutions.*
