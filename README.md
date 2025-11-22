# 🧠 LangChain Tool-Enabled Chatbot (Arxiv, Wikipedia, Tavily & Custom Tools)

This repository contains a fully functional **agentic AI chatbot** built with **LangChain**, **Groq LLaMA 3**, and **LangGraph**.  
The chatbot supports:

- 📄 **Arxiv research search**
- 🌍 **Wikipedia query search**
- 🔎 **Tavily web searches**
- ➕ **Custom function tools** (add, divide, multiply)
- ♻️ **Memory-enabled tool calling**
- 🔧 **ReAct-style agent reasoning**
- 🌐 **Graph-based agent execution using LangGraph**

---

## 🚀 Features

### ✅ 1. **Tool-Enabled LLM Agent**
The chatbot uses **llama3-70b** model from Groq, combined with tools:
- `ArxivQueryRun`
- `WikipediaQueryRun`
- `TavilySearchResults`
- Custom arithmetic tools (`add`, `divide`, `multiply`)

### ✅ 2. **Automatic Tool Calling**
The model automatically:
- Detects user intent  
- Calls the correct tool  
- Returns final conversational answers


