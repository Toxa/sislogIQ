
# 🧠 syslogIQ

**AI-powered syslog analyzer using OpenSearch Neural Search and local LLMs.**  
Make sense of your logs with the power of vector search and natural language.

---

## 🚀 Features

- 🔎 Intelligent log analysis using local LLMs via [Ollama](https://ollama.com/)
- 🤖 Vector-based search using OpenSearch Neural Search
- 🧵 Context-aware exploration of logs around anomalies
- 🪵 Focused on Linux `syslog`, but easily extendable
- 💡 Designed to answer the question: "What happened?"

---

## 📦 Installation

```bash
git clone https://github.com/your-username/syslogIQ.git
cd syslogIQ
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
````

---

## ⚙️ Configuration

Edit the `config.py` (or `.env`) to set:

* `OPENSEARCH_HOST`, `PORT`, and credentials
* `OLLAMA_URL` and model name (e.g., `mistral`, `llama3`)
* Your prompt files: `system.txt` and `user.txt`

---

## 🧪 Usage

```bash
python -m syslogiq
```

Make sure:

* You have a running OpenSearch cluster with vector search enabled.
* Your Ollama model is running locally.

---

## 📁 Project Structure

```text
syslogIQ/
├── main.py             # Entry point (async workflow)
├── config.py           # OpenSearch + Ollama config
├── opensearch_utils.py # Query builders and search helpers
├── llm_client.py       # Ollama client (async)
├── prompts/
│   ├── system.txt
│   └── user.txt
├── requirements.txt
└── README.md
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ❤️ Contributing

Pull requests are welcome! If you have ideas for improving log analysis, feel free to fork and hack.

---

## 🗣️ Why syslogIQ?

Because your logs deserve an **IQ boost**.

```

---

Хочешь — помогу структурировать `pyproject.toml`, `setup.py` или `requirements.txt`, а также разнести код по папкам. Готов продолжить!
```
