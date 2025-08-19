# 🧠 LangChain Conversation Chains & Memory with LCEL

This project is a **hands-on exploration of LangChain’s conversation chains and memory mechanisms** using **LangChain Expression Language (LCEL)**.  
It demonstrates how conversational AI agents can maintain context, recall past interactions, and provide coherent responses across multi-turn dialogues.

---

## 🎯 Objective
To understand and implement:
- Different **memory types** in LangChain
- Usage of **LCEL** for chaining components
- Building **context-aware conversational chatbots**

---

## 🛠️ Features
- ✅ Implementation of **ConversationChain** using LCEL
- ✅ Exploring **BufferMemory, SummaryMemory, and VectorStoreRetrieverMemory**
- ✅ Maintaining chat history across turns
- ✅ Comparative analysis of memory types
- ✅ Custom prompts for enhancing conversational context
- ✅ Real-world GenAI chatbot scenarios



## 🔧 Tech Stack
- 🐍 Python 3.9+
- 🧠 LangChain
- 🧩 OpenAI API
- 📚 FAISS (for retriever memory)
- 🔗 LCEL (LangChain Expression Language)
- Jupyter Notebook

---

## 🚀 How to Run
1. **Clone the repo**
   
   git clone https://github.com/GovindaTak/langchain-conversation-memory.git
   cd langchain-conversation-memory


2. **Install dependencies**

3. **Set your API key**

   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your_api_key_here"
   ```

4. **Run the notebook**

   ```bash
   jupyter notebook notebooks/conversation_memory.ipynb
   ```

---

## 📊 Results & Learnings

* **BufferMemory** → Works best for short-term conversations
* **SummaryMemory** → Useful for long interactions without memory overflow
* **VectorStoreRetrieverMemory** → Powerful for semantic recall of past context
* LCEL simplifies chaining of multiple conversational components

---

## 🧠 Skills Gained

* ✅ Deep understanding of **LangChain memory mechanisms**
* ✅ Hands-on with **LCEL (LangChain Expression Language)**
* ✅ Designing conversational agents with context retention
* ✅ Comparative evaluation of memory types
* ✅ Prompt engineering for conversation flows
* ✅ Practical GenAI project development

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Govinda Tak**
AI & Full Stack Developer | GenAI Enthusiast


