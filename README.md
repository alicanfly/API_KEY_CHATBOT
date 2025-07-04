# 🧠 AI Chat Assistant with LangChain & OpenAI

This project is a command-line AI assistant built using [LangChain](https://www.langchain.com/), [LangGraph](https://www.langchain.dev/langgraph), and OpenAI's `gpt-3.5-turbo`. The assistant accepts user input and can perform calculations or chat interactively.

---

## 💡 Features

- Conversational AI assistant
- Handles mathematical calculations (e.g., `17 * (4 + 9)`)
- Built using LangChain + LangGraph
- Continuous interaction loop until user types `"quit"`

---

## 🚀 How to Run

### 1. **Clone the repository**

```bash
git clone git@github.com:alicanfly/API_KEY_CHATBOT.git
cd API_KEY_CHATBOT
````

### 2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
```

### 3. **Install dependencies**

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install openai langchain langgraph python-dotenv
```

### 4. **Set up your API key**

Create a `.env` file:

```env
OPENAI_API_KEY=sk-...
```

Make sure the `.env` file is in the **same directory** as `proj1.py`.

---

## 🧪 Usage

Run the assistant:

```bash
python proj1.py
```

You'll see:

```
Welcome to your AI assistant
You can tell me to do calculations

You:
```

Type your prompt like:

```
what is the square root of 625
```

To quit, type:

```
quit
```

---

## 📦 Project Structure

```
.
├── proj1.py           # Main script
├── .env               # Your OpenAI API key (never commit this!)
├── README.md          # This file
```

---

## ❗ Troubleshooting

* **Quota exceeded?**
  Go to [https://platform.openai.com/account/usage](https://platform.openai.com/account/usage) to check usage and [add billing details](https://platform.openai.com/account/billing/overview) if needed.

* **API key not loading?**
  Make sure `.env` exists and the script calls `load_dotenv()` before using `ChatOpenAI`.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Ali Waseem**
GitHub: [@alicanfly](https://github.com/alicanfly)

---

## 🙌 Contributions

Pull requests welcome. Feel free to fork and improve!
