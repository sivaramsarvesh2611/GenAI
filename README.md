# Agentic RAG based Personalized Recommendation System

## 🔍 Overview
This project demonstrates a personalized product recommendation system built using
semantic embeddings, vector similarity search, Retrieval-Augmented Generation (RAG),
and agent-based decision logic.

The system understands user intent, retrieves relevant products, explains recommendations,
and suggests cart additions and bundles.

---

## 🧠 Key Features
- Semantic product recommendations using embeddings
- User history based personalization
- RAG-based explanation layer
- Agent logic for cart and bundle suggestions

---

## 🛠️ Tech Stack
- Python
- Sentence Transformers
- FAISS (Vector Database)
- Pandas

---

## ⚙️ How It Works
1. Product descriptions are converted into embeddings
2. User history is embedded for personalization
3. FAISS retrieves semantically similar products
4. Retrieved products are passed as context (RAG)
5. An agent suggests cart items and bundle offers

---

## 🧪 Example Output
- Running Shoes
- Gym Bag
- Protein Shaker

Agent Suggestions:
- Bundle offer on fitness essentials
- Add-on recommendation for fitness tracking

---

## 🚀 Future Improvements
- Integrate real LLM (OpenAI / LLaMA)
- Improve agent reasoning
- Add UI using Streamlit
