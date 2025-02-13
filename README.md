# 🚀 ChatMinimax: A MiniMax-Powered Chatbot with Image Support  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)  
[![LangChain](https://img.shields.io/badge/langchain-compatible-brightgreen)](https://www.langchain.com/)  

## 📌 Overview  

ChatMinimax is a **LangChain-compatible** chatbot powered by [MiniMax](https://www.minimaxi.chat/), supporting **both text and image inputs**. It uses the **OpenAI SDK** to interact with MiniMax APIs and extends `BaseChatModel` to seamlessly integrate into LangChain workflows.  

## ✨ Features  

- 🔥 **Supports Text & Image Inputs**: Accepts both textual prompts and **base64-encoded images**.  
- 🚀 **LangChain Integration**: Fully compatible with LangChain's LLM pipelines.  
- ⚡ **Streaming Support**: Generate responses in real-time.  
- 🔑 **API Key Authentication**: Uses environment variables for API security.  

## 📦 Installation  

```sh
pip install openai langchain-core pydantic
