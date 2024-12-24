**Hybrid search**

In the context of information retrieval, hybrid search often involves blending traditional keyword-based searching with more advanced techniques such as natural language processing (NLP),
semantic search, and machine learning. Most of the e-commerce websites use this hybrid search technique.

Semantic search is an advanced search technique that focuses on understanding the meaning behind a user's query rather than simply matching keywords. It uses concepts, relationships, 
and context to deliver more relevant results.

Now, the question arrises how do we combine outputs of both the search types using weightage?

**Reciprocal Rank fusion in hybrid search**
RRF is a method to combine ranked lists from different retrieval systems (e.g., semantic and lexical search). 
It assigns scores to documents based on their rank in each list and fuses them into a single ranked list.

Key Formula:

![image](https://github.com/user-attachments/assets/094493bf-80bc-4f28-aa22-27cde5612cbd)

**Steps:**
- Compute scores for each document across multiple lists.
- Aggregate scores and sort to get the final ranking.

**Why Use RRF?**
- Combines semantic search (conceptual relevance) and lexical search (exact matches).
- Ensures fair contribution from all models.
- Simple, effective, and resilient to outliers.

**Applications:**
- Search engines, e-commerce, and recommendation systems.
- Hybrid search (text + dense vector embeddings).

