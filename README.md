# QA-System-with-Retrieval-Augmented-Generation-RAG
Using Retrieval-Augmented Generation (RAG) to build an academic writing assistant that provides precise and updated answers based on APA 7th edition style guides.
----
✨ Task Goal
To develop a Gradio-based chatbot that:
- Helps students and researchers understand APA formatting rules
- Retrieves exact and context-rich content from official APA 7 PDF resources
- Communicates with clarity, professionalism, and educational intent

🪛 Methodology
- PDF Loading & Preprocessing: Combines multiple APA style guide PDFs and splits them into semantically meaningful chunks.
- Vector Embedding with FAISS: Converts document chunks into vector embeddings using intfloat/multilingual-e5-small via a custom embedding class.
- Retrieval-Augmented Generation (RAG): Uses a retriever to find relevant document segments and formulates a system prompt for answering queries.
- LLM Integration: Connects to OpenAI-compatible models (e.g., GPT-4 via Groq API) for high-quality response generation.
- Gradio Interface: Offers a user-friendly chatbot interface where users can type questions about APA formatting and get immediate, accurate answers.

🟢 Results
- Supports retrieval of official APA 7 reference examples, citation rules, statistics formatting, and paper setup
- Provides structured, correct, and beginner-friendly answers to user questions
- Delivers real-time interaction through a web interface

🌷 Application
This project can be extended or adapted for:
- 1. Writing support systems in academic institutions
- 2. Automated teaching assistants for writing courses
- 3. Domain-specific format checking bots (e.g., Chicago Style, MLA)
