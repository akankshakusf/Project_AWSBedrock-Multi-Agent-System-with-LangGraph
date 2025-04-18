# 🧠 Multi-Agent City Insight System  
### Built with LangGraph, Mistral, Amazon Bedrock — Supercharged by RAG

**Project layout** -  <img src="https://github.com/akankshakusf/Project_AWSBedrock-Multi-Agent-System-with-LangGraph/blob/master/Diagram1.png" width="100%" />
**Project layout** -  <img src="https://github.com/akankshakusf/Project_AWSBedrock-Multi-Agent-System-with-LangGraph/blob/master/Diagram2.drawio.svg" width="100%" />


> A real-world AI assistant that *thinks, adapts, and helps*, just like a local — powered by a modern multi-agent architecture and Retrieval-Augmented Generation (RAG).--

## 🌟 What’s This About?
This project is my take on building an AI system that’s not just smart — but **truly helpful**.

Imagine asking, *“What’s happening in the city this weekend?”* — and getting a thoughtful answer that checks local events, looks up the weather, even recommends what to wear. That’s exactly what this system does.
It brings together:
- **LangGraph** for managing multiple specialized agents,
- **Mistral models via Amazon Bedrock** for powerful language understanding, and
- **RAG techniques** to pull accurate, live data from both local and online sources.

## 🎯 What I Set Out to Do
- 💡 Build a flexible multi-agent AI app using LangGraph + Mistral
- 🗂️ Blend local structured data (SQLite) with real-time APIs using RAG
- 🧠 Break work into intelligent agents that talk to each other
- 👗 Make helpful, contextual recommendations based on what's happening + the weather

## 🤖 Why This Stands Out
This isn’t a basic chatbot. It’s a **network of agents** — each focused on a specific task. One looks up events. One checks the weather. Another combines everything to give you smart, tailored suggestions.
What really powers it? **RAG (Retrieval-Augmented Generation)** — the key to making LLMs feel grounded and current. Instead of relying only on what the model “knows,” we bring in **fresh data** from trusted sources — local DBs, APIs, and the web.
So the system doesn’t just sound smart — it *is* smart.

## 🧩 How It Works

| Agent                  | What It Does                                                  |
|-----------------------|---------------------------------------------------------------|
| `EventsDB Agent`      | Checks local database for event info                          |
| `Search Agent`        | Looks online using Tavily if local data is missing            |
| `Weather Agent`       | Grabs current weather from OpenWeatherMap                     |
| `Recommendation Agent`| Suggests activities + outfit ideas based on all context       |
| `Analysis Agent`      | Pulls it all together into a human-like final response        |

---

## 🛠️ Tech Behind the Scenes

| Tech/Tool            | Purpose                                               |
|----------------------|-------------------------------------------------------|
| **Amazon Bedrock**   | Deploys Mistral securely and at scale                 |
| **LangGraph**        | Connects and routes the agents intelligently          |
| **LangChain**        | Handles LLM prompts + retrieval logic (RAG)           |
| **SQLite**           | Stores local event data                               |
| **Tavily API**       | Adds search power for online events                   |
| **OpenWeatherMap**   | Provides real-time weather insights                   |

---
## 🏭 Industries & Use Cases

This multi-agent + RAG system can be adapted for a variety of industries:

- **🏦 Banking & Finance**  
  - Personalized financial advice  
  - Fraud detection workflows  
  - Compliance checks  

- **💼 IT & Software**  
  - Incident triage and resolution  
  - Log summarization  
  - DevOps assistants  

- **💊 Healthcare**  
  - Patient triage assistants  
  - Claim validation  
  - Medical Q&A bots  etc


