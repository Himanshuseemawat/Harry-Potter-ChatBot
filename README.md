# Harry-Potter-ChatBot

# Q-A-chatbot-with-LLMs-Harry-Potter

# Overview
- Use Langchain to build a chatbot that can answer questions about Harry Potter books
- Flexible and customizable RAG pipeline (Retrieval Augmented Generation)
- Experiment with various LLMs (Large Language Models)
- Use FAISS vector store to store text embeddings created with Sentence Transformers from 🤗. FAISS runs on GPU and it is much faster than Chroma
- Use Retrieval chain to retrieve relevant passages from embedded text
- Summarize retrieved passages
- Leverage Kaggle dual GPU (2 * T4) with Hugging Face Accelerate
- Chat UI with Gradio


# Models
- <a href="https://huggingface.co/TheBloke/wizardLM-7B-HF">TheBloke/wizardLM-7B-HF</a>
- <a href="https://huggingface.co/daryl149/llama-2-7b-chat-hf">daryl149/llama-2-7b-chat-hf</a>
- <a href="https://huggingface.co/daryl149/llama-2-13b-chat-hf">daryl149/llama-2-13b-chat-hf</a>
- <a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2">mistralai/Mistral-7B-Instruct-v0.2</a>
