# 💸 AI Financial Agent using Phidata

This project is an **Agentic AI system** that acts like a personal financial research assistant. It combines multiple tools—web search, financial APIs, and LLMs—to autonomously answer finance-related questions, retrieve real-time stock data, and provide contextual explanations.

> 🔧 Built by following Krish Naik’s tutorial: [Building Your First Agentic AI - Financial Agent With Phidata](https://www.youtube.com/watch?v=74SnvbQYgx8)

---

## 📌 Project Aim

This project aims to **simulate a financial research assistant** powered by Agentic AI — capable of performing autonomous tasks like:

- 🧠 Understanding and responding to complex financial queries
- 🌍 Searching the web for real-time financial news or facts
- 📊 Fetching and analyzing stock market data from public APIs
- 💬 Responding in natural language using LLMs

With **Phidata’s open-source agent framework**, this project demonstrates how to:
- Build **autonomous agents** that coordinate multiple tools (web search, APIs, LLMs)
- Connect LLMs to **real-time data sources**
- Deploy a **custom financial assistant** that could help analysts, retail investors, or research teams

---

## 💼 Real-World Use Cases

This project can act as the foundation for:

- 🏦 Financial research bots for banks or investment firms
- 📈 Personalized retail investor advisors
- 📰 Real-time market monitoring tools
- 🤖 Chat-based wealth management assistants
- 🔍 AI-powered equity research co-pilots

---

## 🧠 Why Agentic AI?

Agentic AI goes beyond question answering — it mimics human-like workflows:
- Decomposes user goals into sub-tasks
- Uses the right tools for the job (API, search, LLM)
- Makes decisions based on intermediate steps

This project shows how **next-gen AI agents** can automate meaningful work in domains like **finance**, **research**, and **analytics**.

---

## 📁 Project Structure

```
financial-agent/
│
├── .env                      # Contains API keys
├── requirements.txt          # All dependencies
├── financial_agent.py        # Main agent definition
└── playground.py             # Entry point to interact with the agent
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/financial-agent.git
cd financial-agent
```

### 2. Create a Virtual Environment

```bash
conda create -p venv python=3.12 -y
conda activate venv
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Your API Keys

Create a `.env` file in the root directory with the following content:

```env
PHIDATA_API_KEY=your_phidata_api_key
GROQ_API_KEY=your_groq_api_key
```

---

## 🚀 How to Run

Launch the agent playground:

```bash
python playground.py
```

Ask anything like:
- "What is the current stock price of Tesla?"
- "Explain what is EBITDA."
- "Give me latest news about Infosys."

---

## 🧩 Tools & Technologies Used

- [Phidata](https://www.phidata.com/) — Agent framework
- [Groq](https://console.groq.com/) — LLMs (Mixtral, LLaMA)
- [DuckDuckGo Search](https://duckduckgo.com/api) — Real-time information
- [YFinance](https://pypi.org/project/yfinance/) — Stock price and financial data
- Python 3.12, `.env` for secrets

---

---

## 📚 Reference

- [Krish Naik’s Blog](https://www.krishnaik.in/blog/Building%20Your%20First%20Agentic%20AI-%20Financial%20Agent%20With%20Phidata)
- [Phidata Documentation](https://docs.phidata.com/)
- [Groq API Docs](https://console.groq.com/)

---

## 🧠 Credits

Developed with guidance from [Krish Naik](https://www.youtube.com/@KrishNaik), using Phidata’s open-source tooling.

---

## 📝 License

This project is licensed under the MIT License.
