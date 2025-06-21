This project showcases an intelligent pipeline of LLM agents collaborating to answer complex questions using both vector-based PDF retrieval and real-time web search.

🚀 Features
🔍 Routing Agent: Determines whether to use vector search or web search based on the user's query.

📄 PDF Search Agent: Performs semantic search over a technical research paper (e.g., “Attention is All You Need”).

🌐 Web Search Agent: Uses Tavily for retrieving up-to-date information online.

🧪 Grading Agents: Evaluate relevance and factuality of retrieved results.

💬 Answering Agent: Synthesizes a final response or falls back to web search if hallucination is detected.

🧩 Streamlit GUI: Interactive interface for end-users to query the agent system.


🛠️ Tech Stack
crewai==0.28.8

crewai-tools==0.1.6

langchain-community==0.0.29

langchain-openai, langchain-groq, langchain-huggingface

sentence-transformers

Tavily API for web search

Groq API for fast LLM responses

PDFSearchTool for semantic document retrieval

Streamlit for user interface
