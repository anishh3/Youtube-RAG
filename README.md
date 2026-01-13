# 🎥 YouTube Video Q&A Chatbot (RAG)

A Retrieval-Augmented Generation (RAG) based chatbot that answers user questions using the content of a YouTube video.
The system extracts the video transcript, chunks it, stores embeddings, and uses an LLM to generate accurate, context-aware answers.

## 🚀 Features

🔗 Accepts YouTube video URLs

📝 Automatically fetches video transcripts

✂️ Smart text chunking for better retrieval

🧠 Vector-based semantic search

🤖 Context-aware answers using LangChain + LLM

❌ Reduces hallucinations by grounding responses in video content

## 🧠 How It Works (High Level)

User provides a YouTube video link

Transcript is extracted from the video

Transcript is split into overlapping chunks

Chunks are converted into embeddings and stored in a vector database

User asks a question

Relevant chunks are retrieved

LLM generates an answer only using retrieved context
