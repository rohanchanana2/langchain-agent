# ✨ LangChain-Agent

🚀 **LangChain-Agent** is a powerful AI agent powered by **LangChain**, **Groq LLM**, and various tools for search, embeddings, and knowledge retrieval.

## 📌 Features
- 🤖 **LLM-Powered Agent** using `ChatGroq` with `Gemma2-9b-It`
- 🔍 **Web Search Integration** via `TavilySearchResults`
- 📚 **Wikipedia API Wrapper** for quick fact retrieval
- 📄 **Web Scraping & FAISS Vector Store** for document-based queries
- 🛠️ **Custom Tools** including a word length calculator
- 🏗️ **Retrieval-Augmented Generation (RAG)** support

## 🔧 Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/rohanchanana2/langchain-agent.git
   cd langchain-agent
   ```
2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up environment variables**
   - Create a `.env` file in the root directory and add:
   ```ini
   GROQ_API_KEY=your_groq_api_key
   LANGCHAIN_API_KEY=your_langchain_api_key
   GOOGLE_API_KEY=your_google_api_key
   TAVILY_API_KEY=your_tavily_api_key
   ```

## 🛠️ Usage
```python
agent_executor.invoke({"input": "What is LangSmith?"})
```
This will return relevant information using the integrated tools.
