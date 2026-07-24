🛒 LangChain E-Commerce Chatbot

An AI-powered e-commerce chatbot built using Python, LangChain, Streamlit, and Groq LLM. This project demonstrates the core concepts of modern conversational AI, including document processing, vector search, Retrieval-Augmented Generation (RAG) fundamentals, conversational memory, and an interactive chat interface.

⸻

✨ Features

* 📄 Document chunking using LangChain Text Splitters
* 🔍 Semantic search with Chroma Vector Database
* 🧠 Local embeddings using HuggingFace (all-MiniLM-L6-v2)
* 🤖 AI responses powered by Groq Llama models
* 💬 Conversational memory using MessagesPlaceholder
* 🎨 Interactive Streamlit chat interface
* ⚡ Streaming responses for a smooth user experience

⸻

🛠️ Tech Stack

* Python
* LangChain
* Streamlit
* Groq API
* ChromaDB
* HuggingFace Embeddings
* python-dotenv

⸻

📂 Project Structure

.
├── 01_document_chunking.py
├── 02_vector_store.py
├── 03_rag_chain.py
├── 04_chat_memory.py
├── app.py
├── requirements.txt
├── .gitignore
└── README.md

⸻

🚀 Installation

Clone the repository:

git clone https://github.com/your-username/LangChain-ECommerce-Chatbot.git
cd LangChain-ECommerce-Chatbot

Create a virtual environment (recommended):

python -m venv venv

Activate the environment:

Windows

venv\Scripts\activate

macOS / Linux

source venv/bin/activate

Install the required packages:

pip install -r requirements.txt

⸻

🔑 Environment Variables

Create a .env file in the project directory and add your Groq API key:

GROQ_API_KEY=your_api_key_here

⸻

▶️ Run the Chatbot

streamlit run app.py

The chatbot will open in your browser.

⸻

💡 Example Questions

* What is your refund policy?
* How long does shipping take?
* Is Cash on Delivery available?
* What are your support timings?
* How can I contact customer support?

⸻

📚 Concepts Covered

* Document Chunking
* LangChain Documents
* Recursive Character Text Splitter
* Embeddings
* Vector Database (Chroma)
* Similarity Search
* Retriever
* Prompt Engineering
* Retrieval-Augmented Generation (RAG) Basics
* Conversational Memory
* Streamlit Chat Interface

⸻

🔮 Future Improvements

* Product catalog integration
* Order tracking support
* Persistent vector database
* Multi-user authentication
* Chat history export
* Voice-based interaction

⸻

👨‍💻 Author

Tushar Verma

B.Tech CSE (Artificial Intelligence)
Babu Banarasi Das University, Lucknow

⸻

📜 License

This project is created for educational and portfolio purposes.
