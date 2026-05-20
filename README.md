<h1 align="center">MULTIPURPOSE SHOPPING AI 🛍️🤖</h1>

<p align="center">
  <img src="public/shoppinggpt_logo.png" alt="Multipurpose Shopping AI Logo" width="200" height="auto">
</p>

<p align="center">
An AI-powered intelligent shopping assistant built using Generative AI, RAG, Semantic Routing, and advanced NLP techniques for seamless shopping experiences.
</p>

---

# 🚀 Overview

MULTIPURPOSE SHOPPING AI is a smart AI-based shopping assistant that helps users search products, get personalized recommendations, answer policy-related queries, and engage in natural conversations.

The project combines:

- 🧠 Large Language Models (LLMs)
- 📚 Retrieval-Augmented Generation (RAG)
- 🔍 Semantic Search
- 💬 Conversational AI
- ⚡ Fast Product Retrieval using SQLite & FAISS

This project is designed to deliver an intelligent, scalable, and user-friendly e-commerce assistant.

---

# ✨ Features

- 🧠 **AI-Powered Conversations**
  - Uses Google's Gemini model for human-like responses.

- 📚 **RAG-Based Retrieval**
  - Retrieves accurate product and policy information from databases.

- 🔍 **Smart Product Search**
  - Supports partial matching and semantic search.

- 🛣️ **Semantic Query Routing**
  - Routes user queries intelligently using embeddings and similarity search.

- 💬 **Interactive Chatbot**
  - Friendly conversational shopping assistant.

- ⚡ **Fast & Efficient**
  - SQLite for product storage and FAISS for vector search.

- 🎯 **Personalized Recommendations**
  - Helps users discover relevant products easily.

---

# 🏗️ System Architecture

The project follows a modular AI architecture:

## 1. Flask Web Application
- Handles frontend interaction
- Displays chatbot responses

## 2. Semantic Router
- Uses embeddings for intelligent query classification
- Routes queries to:
  - Chitchat handler
  - Shopping agent
  - Policy search system

## 3. Shopping Agent
Handles:
- Product search
- Product recommendations
- Policy-related queries

## 4. Databases
- **SQLite** → Product database
- **FAISS Vector Store** → Policy embeddings

## 5. External AI Services
- Google Gemini API
- Google Generative AI Embeddings

---

# 🧠 AI & NLP Technologies Used

## ✅ Large Language Model
- Gemini 1.5 Flash

## ✅ RAG (Retrieval-Augmented Generation)
- Combines vector retrieval with AI-generated responses.

## ✅ Semantic Router
- Intelligent query routing using embeddings.

## ✅ Cosine Similarity
- Measures semantic similarity between queries.

## ✅ Hugging Face Text Classification Model
Used for:
- Product query detection
- Chitchat classification

Model:
[hang1704/opendaisy](https://huggingface.co/hang1704/opendaisy)

---

# 🗂️ Project Structure

```bash
MULTIPURPOSE_SHOPPING_AI/
│
├── data/
│   ├── products.db
│   ├── products.csv
│   └── policy.txt
│
├── public/
│   ├── shoppinggpt_logo.png
│   ├── interface.png
│   ├── product_search.png
│   └── chitchat_example.png
│
├── shoppinggpt/
│   ├── tools/
│   ├── chains/
│   ├── router/
│   └── embeddings/
│
├── scripts/
│   └── init_db.py
│
├── app.py
├── requirements.txt
└── README.md
