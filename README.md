
PharmaRAG: AI-Powered Document Intelligence for Pharma Teams

PharmaRAG is an AI assistant designed to help pharmaceutical companies search, understand, and interact with their most complex documentation using natural language — instantly and securely.

Powered by Google Gemini and backed by a Retrieval-Augmented Generation (RAG) pipeline, this system brings together structured and unstructured data — from PDFs to microbial images — and transforms it into actionable intelligence.

 --Key Features

-AI Chat for Complex Pharma Docs
  Ask natural language questions like:
  “What are the SOP steps for microbial swab testing?”
  “Show me all mentions of Guaifenesin stability data.”
  Behind the scenes, a RAG pipeline fetches relevant documents, summarizes key insights, and responds contextually using Gemini.
RAG with PDF Embeddings
  Uses LangChain + ChromaDB + GoogleGenerativeAIEmbeddings
  Parses and chunks internal pharma PDFs: SOPs, batch records, microbiology reports, QA documents, etc.
  Fast retrieval of exact paragraphs using kNN search in a vector store.
Visual Interpretation of Microbial Colonies
  Leverages Gemini's multimodal capabilities to understand visual test plates, swab results, or colony counts.
  Users can upload images of agar plates or scanned logs, and the model interprets and compares microbial growth, classifications, and thresholds.
Designed for Pharma Environments
  Developed with regulatory and GMP/GLP workflows in mind
  Handles versioned SOPs, controlled document structures, and diverse PDF formats
  Plug-and-play access through a FastAPI-based web backend

--Tech Stack

LLM: Google Gemini 2.0 Flash (ChatGoogleGenerativeAI)
Embeddings: GoogleGenerativeAIEmbeddings (LangChain)
Vector DB: ChromaDB
RAG Framework: LangChain
PDF Parsing: PyPDF2 + Recursive TextSplitter
Backend: FastAPI + Uvicorn
Frontend: Open source paperless AI code

---Impact

This project has drastically reduced the manual effort required for:

Document search and compliance review
Microbial QA investigations
Regulatory Q&A prep
Pharma teams now spend less time digging through SOPs and more time making decisions — with trusted, AI-generated summaries backed by real document context.
