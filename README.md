I Issue Assistant Workflow using n8n

This project is an AI-powered automation workflow built in n8n that enables users to interact with project/task data through chat and automate follow-up actions such as retrieving Jira issues and creating Google Calendar events.

The workflow uses Groq LLM-based AI agents, memory, and tool integrations to simulate a lightweight intelligent project assistant for productivity and task management.

📌 Features
💬 Chat-based workflow trigger
🤖 AI Agent powered by Groq Chat Model
🧠 Conversation memory support
🎫 Fetch Jira issues automatically
📅 Create events in Google Calendar
🔧 Extensible tool-based architecture
🔗 Supports multi-step AI decision workflows
🏗️ Workflow Overview

The automation flow is structured in the following way:

When Chat Message Received
Acts as the main trigger for user interaction.
AI Agent
Processes user input using a Groq Chat Model
Uses Simple Memory to retain context
Can trigger tools such as Google Calendar
Get an Issue (Jira)
Retrieves issue/task details from Jira
AI Agent 1
Further analyzes the retrieved issue data
Can use memory and external tools
Supports additional orchestration logic
Tool Layer / MCP Integration
Enables future extensibility for custom tool execution

🛠️ Tech Stack
n8n
Groq LLM
Jira API
Google Calendar API
AI Agents
Memory Nodes
MCP / Tool Integrations
