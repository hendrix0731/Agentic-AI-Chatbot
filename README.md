# 🤖 Agentic AI Chatbot

A multi-tool conversational AI system powered by **LangChain**, **LangGraph**, and **Streamlit**, capable of reasoning, searching, and integrating real-world APIs such as **WeatherStack** and **AviationStack**.  
Developed by **Harsh Joshi**, this project demonstrates agentic workflows, API integration, and dynamic tool orchestration in an interactive chat interface.

---

## 🚀 Overview

**Agentic AI Chatbot** is a modular conversational assistant built using **LangGraph** and **Streamlit**.  
It can:
- Fetch real-time **weather data** using WeatherStack API.  
- Retrieve **aviation information** (flights, departures, arrivals) using AviationStack API.  
- Perform **contextual reasoning** with LangChain’s ReAct agent logic.  
- Provide an intuitive **chat interface** for end-user interaction.

This project demonstrates how LLMs can be integrated with external tools and APIs for real-world decision-making and automation.

---

## 🧩 Features

✅ **LangGraph + LangChain Integration** – Enables agentic reasoning and tool management.  
✅ **Streamlit Frontend** – Simple and responsive chat UI for users.  
✅ **WeatherStack API** – Real-time weather details by city.  
✅ **AviationStack API** – Latest flight data and airline insights.  
✅ **OpenAI (ChatGPT)** – Core conversational intelligence.  
✅ **Custom Tools** – Functions wrapped with LangChain’s `@tool` for dynamic API calls.  

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Frontend** | Streamlit |
| **Backend** | LangChain, LangGraph |
| **AI Model** | OpenAI GPT (via LangChain) |
| **APIs** | WeatherStack, AviationStack |
| **Language** | Python |
| **Environment** | `.env` file for API keys |
| **Version Control** | Git + GitHub |

---

## 📁 Project Structure

```
Agentic-AI-Chatbot/
│
├── bot/
│   ├── streamlit_frontend_tool.py     # Streamlit-based chat interface
│   └── langgraph_tool_backend.py      # Backend logic, LangGraph + LangChain agents
│
├── .env                               # Contains API keys (not to be uploaded)
├── requirements.txt                   # Project dependencies
└── README.md                          # Documentation
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/hendrix0731/Agentic-AI-Chatbot.git
   cd Agentic-AI-Chatbot
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv jarvis
   jarvis\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add your environment variables**
   Create a `.env` file in the project root:
   ```
   OPENAI_API_KEY=your_openai_key
   WEATHERSTACK_API_KEY=your_weatherstack_key
   AVIATIONSTACK_API_KEY=your_aviationstack_key
   ```

5. **Run the Streamlit app**
   ```bash
   streamlit run bot/streamlit_frontend_tool.py
   ```

6. **Open the app**
   The chatbot will be available at:
   ```
   http://localhost:8501
   ```

---

## 💬 Example Queries

- “What’s the weather like in Mumbai right now?”  
- “When is the next available flight from Delhi to Singapore?”  
- “How long will it take for flight EK501 to reach Dubai if it departed on time?”  
- “Summarize the latest AI research trends.”  

---

## 🖼️ Screenshots

| Chat Interface | API Response |
|----------------|--------------|
| ![Chat UI](screenshots/Chat_UI.png) | ![API Output](screenshots/API_Output.png) |



---

## 🧠 Learning Highlights

- Implemented **agentic reasoning** using LangGraph and LangChain.  
- Integrated **real-time APIs** for contextual data retrieval.  
- Created an **interactive chat interface** using Streamlit.  
- Demonstrated **tool orchestration** and modular backend design.  

---

## 👨‍💻 Author

**Harsh Joshi**  
📍 B.Tech CSE @ JECRC University (2021–2025)  
💼 Aspiring AI/ML Engineer | Agentic AI & LangChain Developer  

📧 [harsh.joshi.m07@gmail.com](mailto:harsh.joshi.m07@gmail.com)  
🔗 [GitHub – hendrix0731](https://github.com/hendrix0731)  
💼 [LinkedIn – Add Link Here](https://linkedin.com/in/your-link)  

---

## 🌟 Acknowledgements

- [LangChain](https://github.com/langchain-ai/langchain)  
- [LangGraph](https://github.com/langchain-ai/langgraph)  
- [Streamlit](https://streamlit.io)  
- [WeatherStack API](https://weatherstack.com/)  
- [AviationStack API](https://aviationstack.com/)

---

### ⭐ Don’t forget to star the repo if you like this project!
