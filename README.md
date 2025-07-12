# 🕒 Time AI Agent — Fetch Accurate Timezones Using LLM + Tools

🔗 [Live Demo on Hugging Face Spaces](https://huggingface.co/spaces/Bhaskar2611/First_agent)

**Time AI Agent** is a lightweight yet powerful agent that uses an **LLM (Mistral 7B)** integrated with a custom-built timezone tool based on `pytz` to retrieve accurate local time from anywhere in the world.

This project was built as part of the **Hugging Face AI Agents course** and showcases the power of combining LLMs with external tools to overcome limitations like fetching real-time data.

---

## 🌍 What It Does

Large Language Models (LLMs) like Mistral 7B are great at generating and understanding text, but they **can’t access real-time data** like the current time in a given timezone.

That’s where tools come in!

In this agent, we integrated:

- 🔧 **Custom Time Tool** (built using `pytz`)
- 🌐 **Web Search Tool** (optional exploration)
- 🔗 **Visit Webpage Tool** (open URLs)
- ✅ **Final Answer Tool** (formats output)

---

## ⚙️ How It Works

```
User Query → AI Agent (Mistral 7B) → Tool Calls → Real-Time Timezone Result
```

### Example

**User:**  
> What is the current time in Australia?

**Agent:**  
1. Uses `web_search` if needed  
2. Calls `time_zone_tool` to get exact local time in Australia  
3. Formats response via `final_answer`

---

## 🧩 Agent Tools Used

| Tool Name       | Description                                     |
|----------------|-------------------------------------------------|
| `web_search`    | Searches the web for context (if needed)        |
| `visit_webpage` | Visits a URL and retrieves its content          |
| `time_tool`     | Custom tool using `pytz` to get local time      |
| `final_answer`  | Outputs the final answer clearly to the user    |

---

## 🛠️ Tech Stack

| Component        | Description                               |
|------------------|-------------------------------------------|
| `Mistral 7B`     | Open-source LLM (via Hugging Face)         |
| `pytz`           | Python library for timezone data           |
| `Gradio`         | UI to interact with the agent              |
| `Hugging Face Spaces` | Deployment platform                    |

---

## 🚀 Why It Matters

- 🔄 Demonstrates **AI agents** in action by letting LLMs **interact with real-time data**
- 🧠 Great starter project for those exploring **tool-augmented language models**
- 💡 Can be extended to build more sophisticated **calendar bots, schedulers, or assistants**

---

## 📚 Inspiration

Thanks to the amazing [Hugging Face AI Agents Course](https://huggingface.co/learn/agents-course) and the growing open-source ecosystem around **LLMs + tool use**.

---

## 👨‍💻 Author

**Jyothula Bhaskar**  
B.Tech in Computer Science & Engineering (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/bhaskar-jyothula-974bbb271/) | [Hugging Face](https://huggingface.co/Bhaskar2611) | [GitHub](https://github.com/Bhaskar2603) | [Kaggle](https://www.kaggle.com/bhaskarjyothula)

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share it with attribution.
