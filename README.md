# Advanced RAG-Enhanced Document Processing

## Overview  
This project implements a **Retrieval-Augmented Generation (RAG)** system to enhance large language model outputs. The RAG pipeline ensures that responses are accurate, relevant, and context-aware by retrieving key information from external knowledge sources.

## Features  
- **RAG-based System:** Enhances large language models by integrating external knowledge into their responses.  
- **Vector Search:** Efficient retrieval of relevant documents using vector-based similarity.  
- **Automated Workflows:** Orchestrated multiple tasks to ensure smooth and optimal performance.  

## Workflow  
1. **Embedding Creation:**  
   - Generate vector embeddings for documents using **Sentence Transformers**.
2. **Storage:**  
   - Store the generated embeddings in **FAISS** for efficient vector search.
3. **Retrieval:**  
   - Query FAISS to retrieve the most relevant documents based on the input prompt.
4. **Generation:**  
   - Use the retrieved documents to augment the output of a large language model (**LLAMA 3**).
