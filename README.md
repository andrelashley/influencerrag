\# Influencer-RAG



\*\*Influencer-RAG\*\* is a Retrieval-Augmented Generation (RAG) platform designed for influencer workflows. It provides memory-aware conversational experiences, intelligent content triage, and personalized interaction tools using LLMs and contextual data.



Built with \*\*.NET Core MVC\*\* on the backend and a TypeScript-based frontend, this project serves as a flexible foundation for AI-powered fan engagement.



---



\## 🧠 Key Features



\- \*\*Memory-Aware Chat:\*\* Personalized, contextual conversations based on previous interactions and uploaded content.

\- \*\*Content Triage Tools:\*\* Automatically prioritize and summarize incoming content from fans or collaborators.

\- \*\*Modular Architecture:\*\* Clean separation between frontend (TypeScript) and backend (C#) logic.

\- \*\*RAG Integration:\*\* Combines local knowledge with LLM completions for grounded, relevant responses.



---



\## 📁 Project Structure



```

influencer-rag/

├── app/chat/              # RAG engine and chat context logic

├── frontend/              # TypeScript/React frontend (SPA)

├── Controllers/           # ASP.NET Core MVC controllers

├── Models/                # Data models and DTOs

├── Services/              # Business logic and integration services

├── influencerrag.py       # (Optional) Python module for LLM calls or preprocessing

├── appsettings.json       # Configuration and environment variables

└── Program.cs / Startup.cs # ASP.NET Core app bootstrapping

```



---



\## 🚀 Getting Started



\### 1. Prerequisites



\- \[.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)



\### 2. Clone the Repo



```bash

git clone https://github.com/andrelashley/influencerrag.git

cd influencerrag

```



\### 3. Configure Environment



Create a new file:



```bash

cp appsettings.Development.json

```



Edit your settings, API keys, and local paths accordingly.



\### 4. Run the Backend



```bash

dotnet build

dotnet run

```



---



\## ⚙️ Environment Variables



Use `appsettings.json` or user secrets for:



\- OpenAI / local LLM API keys

\- Vector database configuration (if applicable)

\- Storage or file upload settings

\- Persona metadata



---



\## 📝 License



This project is licensed under the \[MIT License](LICENSE).



---



> Built for creators who want smarter tools to manage community interaction, fan messaging, and branded conversations — without needing to be AI experts.

