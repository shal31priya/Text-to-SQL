# Text-to-SQL
🧠 Text-to-SQL Query Generator

Text_to_SQL is an intelligent Streamlit-based app that converts natural language questions into SQL queries and executes them on a connected SQLite database.
It leverages Google Generative AI (Gemini) and LangChain to understand user intent and generate accurate, executable SQL.

🚀 Features

🗣️ Natural Language to SQL — Ask questions like “Show me all students with marks above 90,” and get results instantly.

🧩 SQLite Database Integration — Connect and query your own .db file.

⚡ Google Generative AI + LangChain — Robust LLM-powered query generation.

🧾 Interactive Streamlit UI — Clean, user-friendly interface for asking and viewing results.

🗂️ PDF Support — Parse data from PDFs using PyPDF2 and pdf2image (optional).

🔍 Vector Search (Chroma + FAISS) — Enables efficient data retrieval and semantic search.

🧰 Tech Stack
Component	Technology
Frontend/UI	Streamlit

LLM Integration	Google Generative AI (Gemini)

Framework	LangChain

Database	SQLite (student.db)
Vector Store	FAISS / Chroma
PDF Processing	PyPDF2, pdf2image
Environment	Python 3.10+
