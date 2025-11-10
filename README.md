# Vibe Matcher — AI Internship Prototype (Nexora)

A minimal AI-powered fashion recommendation system that matches user “vibe” queries to fashion products using OpenAI embeddings and cosine similarity. Features evaluation metrics, visualization, and scalability insights (Pinecone/FAISS integration ready).

## Overview
Vibe Matcher uses **text embeddings** and **cosine similarity** to match a user’s vibe-based text query (e.g., “energetic urban chic”) with the most relevant fashion products. It demonstrates a minimal **embedding-based retrieval pipeline**, evaluation metrics, and scalability reflection.

## Features
- Semantic embeddings via **OpenAI’s text-embedding-ada-002**
- Cosine similarity ranking (top-3 matches)
- Latency evaluation and performance logging
- Fallback and edge-case handling
- Extendable to Pinecone or FAISS for scalable vector search

## Run in Google Colab
1. Open the notebook: `Vibe_Matcher_Nexora.ipynb`
2. Add your OpenAI API key as an environment variable (do NOT hard-code it in the notebook):
   ```powershell
   $env:OPENAI_API_KEY = "sk-your-key"
   ```
   or (bash):
   ```bash
   export OPENAI_API_KEY="sk-your-key"
   ```
3. Run all cells sequentially.

## Author
**Kaniska Roy**  
AI/ML & Web Developer | Internship Applicant @ Nexora

## Repository topics / tags
openai, embeddings, recommender-system, ai, nlp, python, internship, nexora, fashion-ai, cosine-similarity, machine-learning, vector-search
