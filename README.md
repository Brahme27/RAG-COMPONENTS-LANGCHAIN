# Folder Structure
This repository is organized into four major folders, each focused on a core RAG component:

# **1. Document Loaders**  
Used to load data from various sources:  
- PDFs (`PyPDFLoader`)  
- Text files (`TextLoader`)  
- XML files (`UnstructuredXMLLoader`)  
- Webpages and URLs (`WebBaseLoader`)  
- Research papers (`ArxivLoader`)

# **2. Text Splitters**  
Split large documents into smaller chunks for efficient processing:  
- `RecursiveCharacterTextSplitter`  
- `CharacterTextSplitter`  
- `HTMLHeaderTextSplitter`  
- `RecursiveJsonSplitter`

# **3. Embeddings**  
Converted text into vector representations using:  
- `OpenAIEmbeddings`  
- `HuggingFaceEmbeddings`  
- `OllamaEmbeddings` (for lightweight local models)

# **4. Vector Stores**  
Stored and retrieved embeddings using:  
- `FAISS`  
- `Chroma`  
Implemented `VectorStoreRetriever` for retrieving the most relevant content.
