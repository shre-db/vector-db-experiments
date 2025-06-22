# Qdrant Vector Database Overview

| Category | Details |
|----------|---------|
| **What is Qdrant** | Open-source vector database written in Rust for storing, searching, and managing high-dimensional vectors. Optimized for similarity search and ML embeddings. |
| **Core API Operations** | • Collections: Create/delete/configure collections<br>• Vectors: Insert/upsert/update/delete vectors with metadata<br>• Search: Similarity search, filtered search, batch operations<br>• Cluster: Distributed deployments, replication, sharding |
| **Key Use Cases** | • Semantic search<br>• Recommendation systems<br>• RAG (Retrieval-Augmented Generation)<br>• Image/video search<br>• Anomaly detection<br>• Personalization |
| **Strengths** | • **Performance**: Rust implementation, HNSW indexing<br>• **Flexibility**: Multiple distance metrics, rich filtering<br>• **Scalability**: Horizontal scaling, clustering, replication<br>• **Developer Experience**: Well-documented REST API, multiple client libraries<br>• **Rich Metadata**: Complex payload storage and filtering |
| **Limitations** | • **Memory Requirements**: Can be expensive for very large datasets<br>• **Complexity**: Overkill for simple keyword search use cases<br>• **Consistency**: Eventually consistent in distributed mode<br>• **Learning Curve**: Requires ML/vector embedding knowledge<br>• **Cost**: Memory and compute requirements scale with data size |
| **Getting Started Tips** | • Start with Docker for local experimentation<br>• Begin with small datasets<br>• Choose appropriate distance metrics for your embeddings<br>• Experiment with indexing parameters (speed vs accuracy)<br>• Design payload structure considering filtering needs |
| **API Interfaces** | REST API and gRPC |
| **Distance Metrics** | Cosine, Euclidean, Dot Product |
| **Client Libraries** | Python, Rust, Go, and others |
| **Deployment** | Docker support, cloud-ready |