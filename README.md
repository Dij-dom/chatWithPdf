# chatWithPdf
This Repo demonstrates how to build a Retrieval-Augmented Generation (RAG) pipeline with LangChain, where an LLM(TheBloke/Mistral-7B-Instruct-v0.2-GGUF)  answers questions about the Apple HBR report by retrieving and grounding responses in document chunks stored in a vector database ChromaDB.  

## Steps Included:
1. Loaded the pdf using PyMuPDFLoader from langchain.
2. Chunking the loaded pdf data using RecursiveCharacterTextSplitter.
3. Embed the chunking using SentenceTransformerEmbeddings.
4. Set up the vector database using the embedded chunks.
5. Setting up the retriever from the vector store.
6. Setting up the generator using the LLm(Mistral-7B-Instruct-v0.2-GGUF).
7. Using a template(System and User) to  generate a rag response.

Stay tuned to get the final working application. 
