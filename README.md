🚀 MCP_Server_Lead_Qualification
---
📌 Project Overview

MCP_Server_Lead_Qualification is an AI-powered real estate lead qualification and site visit booking automation built using n8n, OpenAI, and Google Sheets.

This project demonstrates how conversational AI can be used to qualify leads, schedule site visits, and store booking data automatically in a structured format.
---

🧠 Project Screenshots & Explanation

📸 Screenshot 1: MCP Server – Google Sheets Automation
<img width="1910" height="664" alt="mcp_server_workflow png" src="https://github.com/user-attachments/assets/0286d4d3-fb8a-4433-b580-beb7f538ae10" />


Explanation:
This screenshot represents the MCP Server workflow, which is triggered after the site visit is confirmed.

The workflow:

Receives structured booking data

Appends a new row into Google Sheets

Stores booking details reliably for future use

This separates business logic and data storage, making the system scalable.
---
📸 Screenshot 2: MCP Client – Lead Qualification Workflow
<img width="1909" height="917" alt="mcp_client_workflow png" src="https://github.com/user-attachments/assets/8deaa43b-a173-4152-a7e4-f39ad95ec592" />


Explanation:
This screenshot shows the MCP Client workflow responsible for handling the chat-based lead qualification.

Main components used:

When Chat Message Received (Trigger)

AI Agent

OpenAI Chat Model

Simple Memory

MCP Client Tool

This workflow handles user interaction, AI reasoning, and decision-making.
---
📸 Screenshot 3: Chat Conversation & Lead Qualification
<img width="505" height="611" alt="chat_conversation png" src="https://github.com/user-attachments/assets/9065af07-ad00-44cb-b9de-29791edeafcd" />


Explanation:
This screenshot shows the live chat interaction between the user and the AI chatbot.
The chatbot:

Greets the user

Asks about apartment preferences (2BHK / 3BHK / 4BHK)

Confirms interest in scheduling a site visit

Collects the user’s name and mobile number

Confirms the site visit booking with date and time

This is the lead qualification and booking stage of the project.
---
📸 Screenshot 4: AI Agent Final Output
<img width="1703" height="664" alt="ai_agent_output png" src="https://github.com/user-attachments/assets/7bb865b3-b12a-4fab-b87e-d2af201eb1c1" />


Explanation:
This screenshot displays the AI Agent execution result inside n8n.
The AI Agent:

Processes the entire conversation

Uses memory to maintain context

Generates a structured confirmation message

Confirms that the site visit has been successfully booked

This ensures accurate and professional responses to the user.
---
📸 Screenshot 5: Google Sheets – Stored Booking Details
<img width="1919" height="672" alt="google_sheets_data png" src="https://github.com/user-attachments/assets/fd8e1f03-0da0-4850-85ad-77f188f2ebb4" />


Explanation:
This screenshot shows the Google Sheet where all site visit bookings are stored automatically.

Stored data includes:

Customer Name

Visit Date

Visit Time

User Interest

Booking Summary

This sheet can be used for lead tracking, follow-ups, and reporting.
---
🛠️ Tech Stack
| Component           | Technology              |
| ------------------- | ----------------------- |
| Automation Platform | n8n                     |
| AI Model            | OpenAI Chat Model       |
| Memory              | Simple Memory           |
| Tooling             | MCP Client & MCP Server |
| Data Storage        | Google Sheets           |
| Interface           | n8n Chat (Beta)         |
---
🚀 How to Run the Project

Import workflows into n8n

Configure OpenAI API credentials

Configure Google Sheets credentials

Update Sheet ID and column mapping

Activate both workflows

Start chat using n8n Chat
---

📌 Use Cases

Real estate lead qualification

Site visit booking automation

AI-powered customer interaction

CRM data collection

n8n portfolio project
---

👨‍💻 Author

Dikesh Chavhan
---
