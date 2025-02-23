# 🏛️ Intelligent Legal Decision Support System with AI Automation

The **Intelligent Legal Decision Support System with AI Automation** is an AI-powered legal chatbot that assists users in making informed legal decisions under the Indian Constitution. It uses **Llama 2** for legal response generation and **Pinecone** as a vector database for efficient legal document retrieval.

## 🚀 Features
- **Retrieval-Augmented Generation (RAG):** Ensures responses are backed by relevant legal documents.
- **Llama 2 Integration:** Locally runs **Llama 2 (7B)** to generate legal insights.
- **Efficient Document Search:** Uses **Pinecone** for vector-based retrieval.
- **User-Friendly Interface:** Built with **Streamlit** for seamless interaction.
- **Privacy-Focused:** No external API calls, ensuring data confidentiality.

## 🛠️ Tech Stack
- **Frontend:** Streamlit (Python)
- **Backend:** LangChain, Llama 2 (via CTransformers)
- **Database:** Pinecone (Vector Database)
- **Processing:** HuggingFace MiniLM for embeddings
- **Environment Management:** Python-dotenv

## 📌 System Workflow
1. **User enters a legal query** in the chat interface.
2. **Query is processed** and converted into vector embeddings.
3. **Relevant legal documents** are retrieved from Pinecone.
4. **Llama 2 generates responses** based on retrieved content.
5. **Legal advice is displayed** to the user in a chat format.

## 👨‍💻 Team Members
- **Akash A**
- **Bharathi Priyan T**
- **Dhinesh Kumar T**

Final-year CSE students from **Saveetha Engineering College**.

## 💡 Future Enhancements
- **Fine-tuning Llama 2** with domain-specific legal datasets.
- **Real-time legal updates** for updated laws and regulations.
- **Multilingual support** for better accessibility.

