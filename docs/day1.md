# Day 1 — The Retrieval Problem

## Demo First
Search: "wireless mouse"
Search: "wirless mause"

Why does one fail?

---

## Pipeline
```mermaid
graph LR
    A[User Query] --> B[Tokenization]
    B --> C[Inverted Index]
    C --> D[Matching]
    D --> E[Ranking]
    E --> F[Results]
