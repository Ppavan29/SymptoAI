# SymptoAI – Health RAG Chatbot & Multimodal Assistant

**SymptoAI** is an intelligent, interactive healthcare assistant that integrates a Retrieval-Augmented Generation (RAG) framework with multimodal capabilities for preliminary disease assessment and health triage.

---

## 🚀 Overview
This project leverages modern AI frameworks to retrieve, process, and query medical data efficiently. By combining high-performance vector search with local/hosted LLMs, SymptoAI provides fast, context-aware health insights while minimizing factual hallucinations.

---

## 🛠️ Tech Stack & Architecture
- **Language Model:** Llama-3.2-1B-Instruct (GGUF) / Google Gemini LLM
- **Framework & RAG:** LangChain
- **Vector Database:** FAISS (Facebook AI Similarity Search)
- **Embedding Model:** `all-mpnet-base-v2` / HuggingFace Embeddings
- **Computer Vision:** Deep Learning (CNN) for preliminary dermatological image triage
- **Web Scraping:** Firecrawl (Medical Data Extraction from WebMD)
- **Backend API:** FastAPI
- **Caching & Storage:** Redis
- **Containerization:** Docker & Docker Compose

---

## 📂 Data Sources
- **WebMD:** [https://www.webmd.com/](https://www.webmd.com/)
- Curated Medical Knowledge Bases

---

## 💻 How to Run

### Prerequisites
- Git
- Docker & Docker Desktop
  

1. Clone the repository to your local machine.
   
   ```bash
   git clone https://github.com/Ppavan29/SymptoAI.git
2. After cloning the repo open the terminal on the same folder 

3. create the folder model in root directory

4. download the model from huggingface 
https://huggingface.co/hugging-quants/Llama-3.2-1B-Instruct-Q4_K_M-GGUF

5. place the .gguf file in model directory

6. install docker on you machine 

7. start the docker desktop

8. Run this command in the root directory

   ```bash
   docker-compose up --build 
9. Aplication will start and you can test the api 
http://localhost:8000/docs

10. All done!

