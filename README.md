# AI Financial Advisor – Multi-Agent System

An intelligent **AI-powered financial analysis system** that uses multiple agents to analyze stock data, evaluate risk, and generate investment suggestions.

This project demonstrates how **agent-based AI architectures** can be used to automate financial analysis and decision support.

---

## 🚀 Features

* 📊 Fetch real-time stock data
* 🤖 Multi-agent architecture for analysis
* 📈 Financial metric calculations
* ⚠️ Risk classification (Low / Medium / High)
* 📰 News-based contextual insights
* 💡 AI-generated investment suggestions
* 🌐 Interactive web interface using Flask

---

## 🧠 Multi-Agent Architecture

The system is composed of several specialized AI agents working together:

| Agent              | Role                                        |
| ------------------ | ------------------------------------------- |
| **Data Agent**     | Fetches financial data from APIs            |
| **Analyzer Agent** | Computes financial ratios and insights      |
| **Risk Agent**     | Classifies investment risk                  |
| **News Agent**     | Collects recent news related to the company |
| **Advisor Agent**  | Generates final investment advice           |

### Workflow

User Input (Stock Ticker)
↓
Data Agent → Fetch financial data
↓
Analyzer Agent → Calculate financial metrics
↓
Risk Agent → Determine risk level
↓
News Agent → Gather news context
↓
Advisor Agent → Generate investment suggestion

---

## 🖥️ Web Interface

The project includes a **Flask-based web dashboard** where users can:

* Enter a **stock ticker**
* Run AI financial analysis
* View **decision and risk level**
* Open **detailed AI explanation**

Example output:

Decision: BUY
Risk: Low

---

## 🛠️ Tech Stack

* **Python**
* **Flask**
* **LLM APIs**
* **Financial Data APIs**
* **HTML / CSS**
* **Agent-based architecture**

---

## 📂 Project Structure

```
financial-ai-agents
│
├── agents
│   ├── data_agent.py
│   ├── analyzer_agent.py
│   ├── risk_agent.py
│   ├── news_agent.py
│   └── advisor_agent.py
│
├── templates
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/financial-ai-agents.git
```

Move into the project folder:

```
cd financial-ai-agents
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Flask server:

```
python app.py
```

Then open in browser:

```
http://127.0.0.1:5000
```

---

## 🎯 Example Usage

1. Enter a stock ticker (e.g., **AAPL**)
2. The AI system fetches financial data
3. Agents perform analysis
4. Risk is classified
5. Final AI investment suggestion is generated

---

## 📌 Future Improvements

* Real-time stock price charts
* Portfolio analysis
* Sentiment analysis on financial news
* Advanced financial indicators
* Deployment on cloud platforms

---

## 👨‍💻 Author

Rohith
Aspiring **AI Engineer / Data Scientist**

---

## ⭐ If you like this project

Give the repository a **star ⭐ on GitHub**.
