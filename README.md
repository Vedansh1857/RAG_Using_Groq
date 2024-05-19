# RAG_Using_Groq
## Used Groq Inferencing Engine using 2 models.

### 1. mixtral-8x7b-32768. Used for querying langchain documentation WebPage. For word embeddings used OllamaEmbeddings.
### 2. Llama3-8b-8192. Used for querying the US_cencus PDFs. For word embeddings used HuggingFaceBgeEmbeddings.
### 3. Used FAISS vector stores for both the models.
### 4. Finally, created retrieval chains in both the cases and invoked it for answering the query.
