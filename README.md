# Stock-_Analysis-_Agent


# 🧠 Multi-Agent Financial Insights Assistant

This project is a **multi-agent financial analysis assistant** built using the [Agno](https://pypi.org/project/agno/) framework. It uses **Groq-hosted Llama 3 models**, online tools like **DuckDuckGo** and **Yahoo Finance**, and combines intelligent agents to:

- Fetch real-time financial data
- Search the web and news
- Analyze sentiment from headlines
- Compare companies for investment decisions

---

## ✅ Features

- 🏦 **Finance Analysis** using real-time stock data from Yahoo Finance
- 🌐 **Web Search** insights from DuckDuckGo
- 📰 **News Summary** of latest headlines
- 📈 **Sentiment Analysis** of company news
- 🤖 **Team Agent** for combining all capabilities and giving final investment recommendation

---

## 🔧 Tools & Libraries Used

| Tool / Library       | Purpose                                           |
|----------------------|---------------------------------------------------|
| `agno`               | Framework for building multi-agent LLM systems    |
| `groq`               | Provider of LLaMA 3 models for fast inference     |
| `openai` (optional)  | Can be used for fallback models                   |
| `duckduckgo-search`  | Web search capability for agents                  |
| `yfinance`           | Yahoo Finance integration for financial data     |

---

## 🧠 Large Language Model (LLM)

- **Provider**: Groq API  
- **Model Used**: `llama3-8b-8192`  
- **LLM Host**: Groq Cloud Platform  
- **Why LLaMA 3?**: Fast inference, strong reasoning, open-source architecture.

---

## 🤖 Agents and Their Roles

| Agent Name      | Role/Function                                                                 |
|------------------|-------------------------------------------------------------------------------|
| `web_agent`      | Searches the web for company insights using DuckDuckGo                       |
| `finance_agent`  | Fetches financial data like stock prices, fundamentals, and analyst ratings  |
| `news_agent`     | Gets latest financial news and headlines about the companies                 |
| `sentiment_agent`| Analyzes whether the overall sentiment is Positive, Neutral, or Negative     |
| `agent_team`     | Combines all agents, compares companies, and gives long-term investment advice|

---

## 💡 Example Use Case

The assistant can answer questions like:

> “Analyze companies like Tesla, Nvidia (NVDA), and Apple, and suggest which one to buy for long-term investment.”

It then:
- Collects financial data
- Summarizes recent news
- Analyzes sentiment
- Compares strengths
- Gives a final recommendation

---

## 🚀 How to Run

1. **Install dependencies** (run this in a notebook or terminal):
   ```bash
   pip install agno openai groq duckduckgo-search yfinance
