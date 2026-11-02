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

### Quick Start
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Ppavan29/Health_RAG_ChatBot.git](https://github.com/Ppavan29/Health_RAG_ChatBot.git)
   cd Health_RAG_ChatBot
Download Model Weights:

Create a model directory in the root folder:

Bash
mkdir model
Download the GGUF model file from Hugging Face and place the .gguf file inside the model/ directory.

Launch with Docker:

Ensure Docker Desktop is running.

Run the build command:

Bash
docker-compose up --build
Access the API:

Open your browser and navigate to http://localhost:8000/docs to test interactive endpoints.
