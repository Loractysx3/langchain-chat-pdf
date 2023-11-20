Goal is to  use Langchain to create a ChatGPT for your PDF using Streamlit. 
We will build an application that allows you to ask questions about a PDF document and get answers directly from an LLM (Large Language Model), like OpenAI's ChatGPT

Steps :

1) create an app with streamlit and connect to our OPENAI Key
2) Upload a PDF and extract Text
3) Split text into Chunks
4) Embedding
5) Semantic Search with FB library (FAISS)
6) Knowledge base build
7) User input Question about the PDF
8) Search similarity information (semantic search)
9) Answer with Openai