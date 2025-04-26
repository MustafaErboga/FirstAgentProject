# LangGraph Agent Project

> A simple LangGraph agent powered by OpenAI and Tavily Search.

---

## ✨ Features

- 🧠 Memory-enabled agent using LangGraph
- 🌐 Real-time web search via Tavily
- 🤖 OpenAI GPT-4 as the core LLM
- 💾 Session memory with SQLite (in-memory)
- 🔄 Streaming responses for better interactivity
- 🔥 Fast prototyping setup

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Before running, create a `.env` file:

```dotenv
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
TAVILY_API_KEY=your_tavily_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=FirstAgentProject
```

> ⚡ Don't forget to replace `your_openai_api_key` and others with your actual API keys.

---

## 🚀 Usage

Run the agent:

```bash
python your_script_name.py
```

You will enter an interactive mode.  
Type any question, and the agent will respond, using web search if needed!

Example:

```
> What is the capital of Australia?
(Agent searches with Tavily and answers)
```

---

## 📂 Project Structure

```plaintext
├── main.py           # Main agent execution script
├── .env              # Environment variables
├── requirements.txt  # Python dependencies
├── README.md         # Project documentation
└── assets/           # (Optional) Demo images, gifs
```

---

## 🙌 Acknowledgements

This project is based on an example provided by [LangChain](https://python.langchain.com/).

---

# 🚀 Happy Building!
