
# 7. Demo: Searching by Meaning

Let’s revisit a query:

"device for presentations"

Traditional search relies on Lexical Overlap (TF-IDF, BM25). While fast, it suffers from two major flaws:

- **The Synonym Problem**: Searching "feline" won't find a document containing only the word "cat."

- **Polysemy**: The word "bank" means something different in "river bank" vs. "investment bank."

Semantic Search shifts the focus from matching **words** to matching **meaning** (intent and context).

