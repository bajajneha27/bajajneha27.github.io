
# 10. Retrieval-Augmented Generation

Semantic search is the "Engine" inside the Retrieval-Augmented Generation (RAG) pattern.

---

- **User Query**: "How do I fix a leaky pipe?
- **Retrieve**: Convert query to vector $\rightarrow$ Find top 3 relevant chunks in the Vector DB.
- **Augment**: Feed the retrieved text + the original query into an LLM.
- **Generate**: The LLM provides a grounded, conversational answer.