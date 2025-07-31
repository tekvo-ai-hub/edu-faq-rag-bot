# Internal Faculty FAQ Bot

**Industry:** Education

**Repository:** [tekvo-ai-hub/edu-faq-rag-bot](https://github.com/tekvo-ai-hub/edu-faq-rag-bot)

## Description
Private chatbot for staff FAQs using campus policy and HR documents.

## Requirements
### Functional
- Upload HR & policy docs.
- Answer common questions.
- Highlight policy excerpts.
### Non-Functional
- Runs locally in browser.
- Fast document ingestion.
- Low resource usage.
## Solution Design
**LLM:** Phi-3-mini
**Vector DB:** ChromaDB

### Components
- Web Uploader
- Doc Embedder
- Local RAG Agent
- Context Viewer
### Data Flow
$ Docs → Parse → Embed → Search → Prompt → LLM → Answer

### Tech Stack
- **Frontend:** Vue.js
- **Backend:** Node.js
- **Storage:** Local IndexedDB
- **Deployment:** Browser
