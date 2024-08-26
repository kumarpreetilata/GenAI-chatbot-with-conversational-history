Models: for embedding- HuggingFaceEmbedding(all-MiniLM-L6-v2), for LLM- 'Llama3-8b-8192'
The data is ingested using a .txt file and is broken down into small chunks with overlaps and fed into HuggingFaceEmbedding model. 
The vectorised data is stored into Chroma and is used for retaining conversation history as with the help of Prompt Templates.
We have used Groq for faster retrieval of outputs.
We ahve alo utliised RAG chain to get contextualised output along with conversational history for efficient QnA.
