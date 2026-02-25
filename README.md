Local LLM Chatbot using Phi-3 (Ollama)

This project demonstrates how to build and interact with a local Large Language Model (LLM) using Microsoft Phi-3 via Ollama.
It includes examples of single prompts, streaming responses, multi-turn chat memory, and custom system prompts — all running locally without external APIs.

Features

 Run Phi-3 locally using Ollama
 Basic chatbot interaction
 Streaming responses (token-by-token output)
 Multi-turn conversation with memory
 Custom system prompts & temperature control
 Beginner-friendly notebook format

 Tech Stack

Python

Ollama

Phi-3 LLM

Jupyter Notebook

 Installation & Setup
 Install Ollama

Download from:

👉 https://ollama.com/

After installation, start the Ollama server:

ollama serve
 Pull Phi-3 Model
ollama pull phi3

This downloads the local LLM model.

 Install Python Library
pip install ollama
 Run Notebook

Open:

chatbot_phi3.ipynb

Run cells step-by-step.

 Project Workflow
✔ Model Check

Verifies whether Phi-3 is downloaded locally.

✔ Single Prompt Chat

Simple chatbot query example.

✔ Streaming Response

Displays output token-by-token like ChatGPT typing.

✔ Multi-Turn Conversation

Maintains chat history for contextual responses.

✔ Custom Settings

Control:

Temperature (creativity)

Token limits

Sampling parameters

 Example Use Cases

Local AI chatbot development

Offline AI experimentation

Prompt engineering practice

LLM research and testing

Coding assistants without API costs

 Why Local LLM?

No API cost

Privacy friendly

Offline usage

Faster experimentation

 Future Improvements

Web UI integration

RAG pipeline integration

Document Q&A chatbot

Voice assistant integration

 Author

Amisha Singh
AI/ML Enthusiast | Future ML Engineer

GitHub:
 https://github.com/AmishaSingh0408
