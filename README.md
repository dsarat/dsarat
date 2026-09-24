👋 Sarat Kumar Duvvu

Senior Full Stack .NET Developer | C# | ASP.NET Core | .NET 8 | REST APIs | SQL | Azure | AI

<p align="center">
  <img src="https://img.shields.io/badge/.NET-8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 8"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RBAC-Security-6f42c1?style=flat-square" alt="RBAC"/>
  <img src="https://img.shields.io/badge/SAP-Integration-0FAAFF?style=flat-square" alt="SAP"/>
  <img src="https://img.shields.io/badge/RFID-Track%20%26%20Trace-00897B?style=flat-square" alt="RFID"/>
  <img src="https://img.shields.io/badge/GitLab-CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab CI/CD"/>
  
</p>

👨‍💻 About Me

I am a Senior Full Stack .NET Developer with 8+ years of experience designing and delivering enterprise applications across manufacturing and BFSI domains.

My core experience includes C#, ASP.NET Core, .NET 8, REST APIs, Entity Framework Core, SQL Server, PostgreSQL, Angular, RBAC, SAP integration, Azure services, CI/CD, Hangfire and SignalR.

In my current manufacturing project, I work on an RFID-based Track & Trace platform integrated with SAP. The solution automates warehouse and material movement workflows and has reduced manual data entry by approximately 80%.

Note: Azure and AI topics marked as Learning / Next Focus below are learning goals, not claims of production expertise.

🧰 Technology Stack

Area

Technologies

Languages

C#, SQL/T-SQL, JavaScript, TypeScript

Backend

.NET 8, ASP.NET Core, ASP.NET MVC, Web API, Entity Framework Core, LINQ

Architecture

REST APIs, Microservices, 3-Tier Architecture, SOLID, Dependency Injection, Repository Pattern

Databases

SQL Server, PostgreSQL, Stored Procedures, Indexing, Query Optimization

Security

JWT, RBAC, Identity, OAuth2, API Versioning

Frontend

Angular, JavaScript, TypeScript, jQuery, HTML5, CSS3

Cloud

Azure App Services, Azure Functions, Azure Blob Storage

Background / Real-Time

Hangfire, SignalR

DevOps

GitLab CI/CD, Git

Testing

NUnit, Integration Testing, Code Reviews, Debugging

Enterprise Integration

SAP APIs, RFID systems

AI-Assisted Development

GitHub Copilot, ChatGPT for code generation, testing, documentation, debugging and refactoring

🏭 Featured Project — Track & Trace

RFID + .NET + PostgreSQL + SAP Integration

The Track & Trace application supports manufacturing warehouse and material movement processes.

Core business flow

flowchart LR
    A[RFID / Scanner] --> B[Angular UI]
    B --> C[.NET 8 REST API]
    C --> D[Business / Validation Layer]
    D --> E[(PostgreSQL)]
    E --> F[SAP API]
    F --> G[SAP]
    C --> H[Hangfire / Background Jobs]
    H --> I[Movement History]

Key workflows

Pallet-to-spool / inventory mapping

Pallet decoupling

Put-away

Pickup

Production movement

Pallet remapping

Warehouse inbound and outbound integration

SAP synchronization

RFID movement tracking

Error handling, logging and retry mechanisms

Selected impact

Delivered 15+ enterprise REST APIs using .NET 8.

Automated pallet tracking workflows, reducing manual data entry by approximately 80%.

Implemented scalable RBAC with hierarchical roles and fine-grained permissions.

Optimized SQL queries, indexes and API execution paths for production workloads.

Built background processing with Hangfire and PostgreSQL jobs.

Worked with SAP consultants, RFID teams, QA and business stakeholders.

☁️ Azure Learning Roadmap

The goal is to strengthen my existing .NET experience with practical Azure application-development skills.

Phase 1 — Azure Fundamentals

Azure subscriptions, resource groups and regions

Azure Portal

Azure CLI

Azure Developer CLI (azd)

Microsoft Entra ID

Managed Identity

Key Vault

Application Insights

Azure Monitor

Phase 2 — .NET Application Hosting

Deploy ASP.NET Core API to Azure App Service

Configuration and environment variables

Deployment slots

Application settings

Managed Identity authentication

Application Insights logging and telemetry

Scale-up vs scale-out

Phase 3 — Serverless & Background Processing

Azure Functions

HTTP triggers

Timer triggers

Queue triggers

Durable Functions fundamentals

Compare Azure Functions with Hangfire

Phase 4 — Storage & Data

Azure Blob Storage

Azure Storage Queues

Azure SQL

PostgreSQL on Azure

Connection security

Managed Identity

Backup and recovery concepts

Phase 5 — DevOps

GitHub Actions

Azure DevOps Pipelines

GitLab CI/CD + Azure deployment

Infrastructure as Code fundamentals

Docker

Azure Container Apps

Azure Kubernetes Service (AKS) fundamentals

🤖 AI Learning Roadmap for a .NET Developer

Microsoft's current .NET AI guidance includes Microsoft.Extensions.AI, Azure OpenAI, Azure AI Foundry, vector search, RAG and agent-oriented application development. These are the areas I plan to learn through hands-on .NET projects.

1. Generative AI Fundamentals

LLM fundamentals

Tokens and context windows

Prompt engineering

System vs user prompts

Structured output

Function / tool calling

Embeddings

Temperature and model parameters

AI safety and responsible AI

2. Azure OpenAI + .NET

Azure OpenAI concepts

Azure OpenAI SDK for .NET

Microsoft.Extensions.AI

Chat completion

Streaming responses

Structured responses

Tool/function calling

Keyless authentication with Azure identity

Secure secret management with Key Vault

Example target architecture:

flowchart TD
    A[Angular / Client] --> B[ASP.NET Core API]
    B --> C[Microsoft.Extensions.AI]
    C --> D[Azure OpenAI]
    B --> E[Azure AI Search]
    E --> F[(Documents / Indexed Data)]
    B --> G[Business APIs]
    G --> H[(SQL / PostgreSQL)]

3. RAG — Retrieval-Augmented Generation

Document ingestion

Chunking

Embeddings

Vector search

Hybrid search

Semantic ranking

Grounded responses

Citation / source tracking

RAG evaluation

Target project: Build a Track & Trace Knowledge Assistant that answers questions from application documentation, process documents and operational knowledge.

4. Azure AI Search

Indexes and documents

Keyword search

Vector search

Hybrid search

Semantic ranking

Filters

RAG integration

5. AI Agents

Agent concepts

Tools / plugins

Function calling

Multi-step workflows

Agent memory concepts

Microsoft Agent Framework

MCP fundamentals

Target project: Build an IT Support Agent that can classify an issue, search internal documentation and call approved .NET APIs.

6. Semantic Kernel

Kernel concepts

Chat completion

Plugins

Function calling

Prompt templates

Azure OpenAI integration

Agent/workflow concepts

🧠 AI Tools to Learn

Tool / Technology

Goal

Microsoft.Extensions.AI

Provider-independent AI abstractions in .NET

Azure OpenAI

Enterprise generative AI integration

Azure AI Foundry

Build, evaluate and deploy AI applications/agents

Azure AI Search

Semantic, vector and hybrid search

Microsoft Agent Framework

Build agentic workflows

Semantic Kernel

AI orchestration and plugins

Microsoft.Extensions.VectorData

Work with vector stores through .NET abstractions

Azure AI Document Intelligence

Extract information from documents

Azure AI Speech

Speech-to-text / text-to-speech scenarios

GitHub Copilot

AI-assisted coding and developer productivity

ChatGPT

Debugging, learning, documentation and structured problem solving

MCP

Connect AI agents with tools and external capabilities

🚀 Hands-on Projects I Plan to Build

Project 1 — AI-Powered Track & Trace Assistant

Stack

Angular → ASP.NET Core → Azure OpenAI → Azure AI Search → PostgreSQL

Features:

Ask questions about Track & Trace processes

Search project documentation

RAG-based answers

Source references

Role-based access

API-based business actions

Conversation logging

Project 2 — .NET Document Intelligence API

Stack

ASP.NET Core → Azure AI → Blob Storage → PostgreSQL

Features:

Upload PDF/document

Extract information

Classify documents

Store metadata

Search extracted information

Generate structured JSON

Project 3 — Production Support AI Assistant

Stack

ASP.NET Core → Azure OpenAI → AI Search → Application Insights

Features:

Analyze application errors

Search known issues

Summarize logs

Suggest troubleshooting steps

Retrieve related incidents

Generate production-support summaries

📚 Learning Path

flowchart LR
    A[.NET 8] --> B[Azure Fundamentals]
    B --> C[App Service]
    C --> D[Functions]
    D --> E[Identity + Key Vault]
    E --> F[Azure OpenAI]
    F --> G[Microsoft.Extensions.AI]
    G --> H[Embeddings]
    H --> I[Azure AI Search]
    I --> J[RAG]
    J --> K[Agents]
    K --> L[MCP / Agent Workflows]

Priority order

1. Azure Fundamentals
↓
2. App Service + Functions
↓
3. Identity + Key Vault + Monitoring
↓
4. Azure OpenAI + Microsoft.Extensions.AI
↓
5. Embeddings + Vector Search
↓
6. Azure AI Search + RAG
↓
7. Agents + Tool Calling
↓
8. MCP + Production AI Architecture

🏆 Career Focus

My target profile is:

Senior Full Stack .NET Developer → Azure Cloud Developer → AI-enabled .NET Developer

The objective is not to move away from .NET development, but to combine my existing enterprise development experience with:

C# + .NET 8
      +
ASP.NET Core + REST APIs
      +
SQL + PostgreSQL
      +
Azure
      +
AI / GenAI
      +
RAG
      +
Agents
      =
Modern Enterprise .NET Developer

📈 Current Strengths vs Next Learning

Area

Current Position

Next Goal

C# / .NET

🟢 Strong

Advanced

ASP.NET Core

🟢 Strong

Architecture

REST APIs

🟢 Strong

Distributed systems

SQL / PostgreSQL

🟢 Strong

Cloud databases

Angular

🟢 Working knowledge

Advanced

SAP Integration

🟢 Project experience

Enterprise integration

Azure

🟡 Experience / continuing learning

Production cloud architecture

AI-assisted development

🟡 Current usage

AI application development

Azure OpenAI

🔵 Learning

Hands-on projects

RAG

🔵 Learning

Production-style project

Azure AI Search

🔵 Learning

Vector + hybrid search

Agents

🔵 Learning

Tool calling + workflows

MCP

🔵 Learning

.NET agent integrations

Legend: 🟢 Current strength · 🟡 Existing experience / developing · 🔵 Learning goal

📫 Connect

LinkedIn: linkedin.com/in/saratkumar

Email: dsaratkumar@gmail.com

📖 Official Learning Resources

.NET AI Developer Guide

Build an AI Chat App with .NET

Develop .NET Apps with AI Features

Azure OpenAI for .NET

Azure AI Search for .NET

Build a .NET Vector Search App

Semantic Kernel

Develop AI Apps on Azure
