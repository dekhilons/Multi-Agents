# AI Agent with LangGraph & OpenAI

This project implements an AI workflow using **LangGraph**, **OpenAI**, and **DuckDuckGo Search** to create a multi-agent system.  

## 🛠️ Installation

Install the required dependencies:

```sh
pip install langgraph-supervisor langchain-openai langchain langchain_community langgraph duckduckgo-search 
```

## 🚀 Usage

The project includes:

A math agent that can perform addition and multiplication.

A research agent that can fetch real-time information from DuckDuckGo.

A supervisor that decides whether to use the math or research agent.
Example Usage:

python
Copy
Edit
result = app.invoke({
    "messages": [
        {
            "role": "user",
            "content": "what is quantum computing?"
        }
    ]
})