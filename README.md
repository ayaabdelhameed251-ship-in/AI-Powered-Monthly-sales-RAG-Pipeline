# 📊 AI-Powered Monthly Sales RAG Pipeline

A sophisticated Retrieval-Augmented Generation (RAG) automation pipeline built with **n8n**. This workflow processes monthly sales queries, retrieves contextual knowledge using vector embeddings, and generates intelligent responses powered by Llama models via Groq.

---

## 🌟 Key Features

* **RAG Architecture:** Leverages **Supabase Vector Store** and Embeddings to deliver highly accurate context-aware responses from internal sales documentation.
* **LLM Integration:** Powered by **Groq Chat Model** for ultra-fast and reliable AI completions.
* **Conversational Memory:** Uses **Simple Memory** nodes to maintain session context across multi-turn user queries.
* **Action Routing & Email Integration:** Automatically routes actions and generates/sends structured reports via **Gmail**.

---

## 🛠️ Tech Stack

* **Automation Engine:** [n8n](https://n8n.io/)
* **LLM Model:** Groq (Llama-3.3)
* **Vector Store & Embeddings:** Supabase Vector Store
* **Integrations:** Gmail API, Chat Trigger

---

## 🚀 How to Import & Use

1. **Download the Workflow JSON Files:**
   Download the `.json` workflow files from this repository.

2. **Import into n8n:**
   * Open your n8n instance.
   * Click on the top-right menu `...` > **Import from File**.
   * Upload the downloaded `.json` files.

3. **Configure Credentials:**
   * **Groq API Key:** Add your Groq API credentials.
   * **Supabase Connection:** Set up your Supabase database host, URL, and service key for the Vector Store.
   * **Gmail OAuth2:** Connect your Gmail account to enable direct email responses.

4. **Activate:**
   Toggle the workflow status to **Active** to begin serving queries.
