# 🚀 ChatMinimax: A MiniMax-Powered Chatbot with Image Support  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)  
[![LangChain](https://img.shields.io/badge/langchain-compatible-brightgreen)](https://www.langchain.com/) 
[![MiniMax](https://img.shields.io/badge/MiniMax-Supported-blue?style=flat&logo=appveyor)](https://filecdn.minimax.chat/public/969d635c-cab6-45cc-8d61-47c9fe40c81f.png?x-oss-process=image/format,webp)


## 📌 Overview  

ChatMinimax is a **LangChain-compatible** chatbot powered by [MiniMax](https://www.minimaxi.com/en), supporting **both text and image inputs**. It uses the **OpenAI SDK** to interact with MiniMax APIs and extends `BaseChatModel` to seamlessly integrate into LangChain workflows.  

## ✨ Features  

- 🔥 **Supports Text & Image Inputs**: Accepts both textual prompts and **base64-encoded images**.  
- 🚀 **LangChain Integration**: Fully compatible with LangChain's LLM pipelines.  
- ⚡ **Streaming Support**: Generate responses in real-time.  
- 🔑 **API Key Authentication**: Uses environment variables for API security.  

## 📦 Installation  

```sh
pip install openai langchain-core pydantic
```
