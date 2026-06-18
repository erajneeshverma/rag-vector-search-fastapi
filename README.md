# High-Performance RAG & Vector Search Service

A FastAPI-based semantic search service using Redis HNSW indexing and sentence-transformer embeddings.

## Features
- Document ingestion & chunking
- Batched embedding generation using Sentence-Transformers
- Approximate Nearest Neighbor search (HNSW)
- Redis-based vector storage with caching
- Low-latency semantic search over 100k+ vectors
- Dockerized for easy deployment


## Performance
- Indexed 100k+ vectors using Redis HNSW
- Achieved ~20x latency improvement vs brute-force cosine search
- Controlled recall and memory footprint via HNSW parameters