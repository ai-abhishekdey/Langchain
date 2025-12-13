## Text Embedding models

Text Embedding models transform raw text such as a sentence, paragraph, or tweet into a fixed-length vector of numbers that captures its semantic meaning. These vectors allow machines to compare and search text based on meaning rather than exact words.

### How it works

* **Vectorization** — The model encodes each input string as a high-dimensional vector.

* **Similarity scoring** — Vectors are compared using mathematical metrics to measure how closely related the underlying texts are.
​
### Similarity metrics

Several metrics are commonly used to compare embeddings:

1. **Cosine similarity** — measures the angle between two vectors.

2. **Euclidean distance** — measures the straight-line distance between points.

3. **Dot product** — measures how much one vector projects onto another.


## Open-source Embedding Models

**Sentence-BERT (SBERT)**

```
all-MiniLM-L6-v2 → 384 dims

all-mpnet-base-v2 → 768 dims

```
## Closed-source Embedding Models

**OpenAI text-embedding models**

```
text-embedding-3-small → 1536 dims

text-embedding-3-large → 3072 dims

```

## LangChain Text Embedding Interface

* LangChain provides a standard interface for text embedding models via the **Embeddings** interface.

* Two main methods are available:

1. **embed_query :** Embeds a single query

2. **embed_documents :** Embeds a list of documents

## References:

1. [Langchain Embedding Model Documentation](https://docs.langchain.com/oss/python/integrations/text_embedding/index#embedding-models)

2. [CampusX Youtube Channel](https://youtu.be/HdcLE8JuMrA?si=s-mgIPc5Z8Jaym_7)
