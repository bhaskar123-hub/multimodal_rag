# multimodal_rag

![image](https://github.com/user-attachments/assets/43ca43d5-59c4-4204-b717-b4f0704b53b3)

## Overview  
This repository implements a **Multimodal Retrieval-Augmented Generation (RAG)** pipeline that processes text and images extracted from PDFs. It enables efficient information retrieval and response generation by integrating various AI models.  

## Components  

### Embedding Model  
- **[BAAI/bge-small-en-v1.5](https://huggingface.co/BAAI/bge-small-en-v1.5)** – Generates embeddings for both text chunks and image captions.  

### Image Captioning  
- **[Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)** – Generates captions for images extracted from PDFs.  

### Vector Store  
- **[FAISS (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)** – Stores and retrieves embeddings for text and image captions.  

### LLM (Language Model)  
- **[microsoft/phi-2](https://huggingface.co/microsoft/phi-2)** – Generates responses based on retrieved multimodal context.  

### PDF Processing  
- **[PyMuPDF (fitz)](https://pymupdf.readthedocs.io/)** – Extracts text and images from PDFs.  

### Image Handling  
- **[Pillow (PIL)](https://pillow.readthedocs.io/)** – Processes extracted images.  

### Text Chunking  
- **[RecursiveCharacterTextSplitter (LangChain)](https://python.langchain.com/docs/modules/data_connection/document_transformers/text_splitter)** – Splits extracted text into manageable chunks.  

## Results  

![image](https://github.com/user-attachments/assets/0b0cd2bd-4858-4629-b1f3-2a24dae05e7a)  
![image](https://github.com/user-attachments/assets/139b1abd-3d1f-4b59-b003-9fe97b563b92)  




