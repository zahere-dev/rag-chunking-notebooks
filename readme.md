# Advanced RAG Chunking

## Description
This project explores and compares the performance of three chunking techniques: Fixed-Size, Recursive, and Semantic Chunking. Chunking is crucial for improving retrieval-augmented generation (RAG) by determining how text is split for embeddings and search.

## Resources
- **YouTube Video**: [Performance of Fixed-Size vs Recursive vs Semantic Chunking](https://www.youtube.com/watch?v=jEzh4IuTWtc)

- **Colab Notebooks**:
  - [Fixed-Size Chunking](https://colab.research.google.com/drive/1rl5VHr5KfpUwEk28GCekISza4yG6yRGu#scrollTo=p0Og54mXSZkm)
  - [Recursive Chunking](https://colab.research.google.com/drive/1YvHZZObiz6gNdfBkmOkR61S1fcB_GZ1W#scrollTo=p0Og54mXSZkm)
  - [Semantic Chunking](https://colab.research.google.com/drive/1yqOSKGwqh2c9wPrerr6YDLgIp0qOQgcm#scrollTo=fv0tuXVo7Cqv)
 
- **Dataset**:
  - [Medical Case Studies Synthetica Dataset](https://github.com/zahere-dev/rag-chunking-notebooks/blob/main/medical_case_studies_synthetica_dataset.txt)



## Overview
- **Fixed-Size Chunking**: Divides text into fixed-length segments, which may or may not respect sentence boundaries.
- **Recursive Chunking**: Uses a recursive strategy to create chunks, attempting to preserve context and meaning by breaking text at natural linguistic boundaries.
- **Semantic Chunking**: Leverages the semantic meaning of the text, ensuring each chunk is contextually meaningful, often improving retrieval precision.

Feel free to explore each approach and watch the accompanying video for an in-depth explanation!
