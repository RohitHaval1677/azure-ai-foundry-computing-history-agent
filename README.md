# Azure AI Foundry Computing History Agent

## Overview
This project demonstrates the development and deployment of a domain-specific AI Agent using Microsoft Azure AI Foundry. The agent specializes in answering questions related to the history of computing, pioneering computer scientists, major technological milestones, and vintage computer systems.

The project includes a Flask-based web application that communicates with an Azure AI Foundry Agent using the OpenAI Responses API and Azure Identity authentication.

## Features
  1. Domain-specific AI agent focused on computing history
  2. Built and deployed using Azure AI Foundry
  3. Interactive web interface using Flask
  4. Azure Identity authentication
  5. Conversation history management
  6. Secure environment variable configuration
  7. Markdown response rendering
  8. Scope-controlled responses for non-computing-history questions

## Architecture
  User
    │
    ▼
  Flask Web Application
    │
    ▼
  Agent Client (Python)
    │
    ▼
  Azure AI Foundry Agent
    │
    ▼
  GPT-4.1-mini

## Tech Stack
  | Technology           | Purpose                        |
  | -------------------- | ------------------------------ |
  | Python               | Backend Development            |
  | Flask                | Web Framework                  |
  | Azure AI Foundry     | Agent Development & Deployment |
  | Azure Identity       | Authentication                 |
  | OpenAI Responses API | Agent Communication            |
  | HTML/CSS/JavaScript  | Frontend                       |
  | Git & GitHub         | Version Control                |

## Screenshots
1. Agent Creation in Azure AI Foundry
2. Agent Configuration and Development
3. Chat Interface
4. Successful Agent Response
5. Off Topic Rejection

## Project Structure
azure-ai-foundry-computing-history-agent
│
├── computer-history-client
│   ├── static
│   ├── templates
│   ├── agent_client.py
│   ├── app.py
│   └── requirements.txt
│
├── screenshots
│   ├── agent-created.png
│   ├── foundry-agent.png
│   ├── chat-interface.png
│   └── chat-response.png
│   └── off-topic-rejection.png
│
├── .gitignore
├── .env.example
├── LICENSE
└── README.md

## Setup Instructions
git clone https://github.com/RohitHaval1677/azure-ai-foundry-computing-history-agent.git
cd azure-ai-foundry-computing-history-agent

##Install Dependencies
pip install -r computer-history-client/requirements.txt

##Configure Environment Variables
  Create a .env file inside computer-history-client:
  
  AGENT_ENDPOINT=YOUR_AGENT_ENDPOINT
  AGENT_NAME=YOUR_AGENT_NAME
  AGENT_VERSION=YOUR_AGENT_VERSION

##Run Application
  cd computer-history-client
  python app.py

  Open: http://127.0.0.1:5000

## Example Questions
What was ENIAC?
Why is Alan Turing considered the father of computer science?
How did computing evolve from mainframes to cloud computing?
What were the major milestones in Artificial Intelligence before modern LLMs?
Explain the five generations of computers.
How did UNIX influence modern operating systems?

## Learning Outcomes
Through this project I gained hands-on experience with:

  Azure AI Foundry Agent creation
  Agent deployment and publishing
  Azure Identity authentication
  OpenAI Responses API integration
  Flask web application development
  Environment variable management
  Building domain-specific AI assistants
  GitHub project documentation

## Future Enhancements
  Agent memory integration
  Knowledge base integration
  Voice-enabled interactions
  Historical timeline visualizations
  Azure deployment for public access
  Multi-agent architecture
