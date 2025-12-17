## Vector Stores

A vectore store stores vector embeddings and performs similarity search


### Interface

LangChain provides the following interfaces

* **add_document** - Add documents to the store.

* **delete** - Remove stored documents by ID.

* **similarity_search*** - Returns the closest embedded documents

### Similarity metrics & indexing

Embedding similarity may be computed using:

* **Cosine similarity**

* **Euclidean distance**

* **Dot product**

### Popular Langchain-vector stores integrations

* [Chroma](https://docs.langchain.com/oss/python/integrations/vectorstores/chroma)

* [FAISS](https://docs.langchain.com/oss/python/integrations/vectorstores/faiss)

* [Pincone](https://docs.langchain.com/oss/python/integrations/vectorstores/pinecone)

* [Qdrant](https://docs.langchain.com/oss/python/integrations/vectorstores/qdrant)

## References:

* [Langchain vector stores documentation](https://docs.langchain.com/oss/python/integrations/vectorstores/index#vector-stores)
