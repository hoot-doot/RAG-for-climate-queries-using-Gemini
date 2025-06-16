# RAG-for-climate-queries-using-Gemini
This application is a smart FAQ assistant that leverages ChromaDB for vector similarity search and Gemini (Google Generative AI) for natural language responses. It processes structured FAQ data, creates embeddings, and serves responses based on confidence thresholds optionally handing off to a live agent if needed.

 ## Features
- Semantic Search with ChromaDB: Stores and retrieves FAQ pairs using embeddings for accurate question matching.

- Generative Responses with Gemini: Generates human-like answers when FAQs are not an exact match.

- Confidence-Based Handoff: Escalates to a live agent when confidence is low.

- Few-Shot Prompting: Enhances complex query handling using examples.
