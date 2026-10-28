# claims-helper
Claims Helper is for understanding the status of the claim

What the Claims Helper does
1. Takes a question such as "Why was this claim denied and what should the office do next?"
2. Searches your synthetic denial-code and payer-rule documents (the retrieval, or RAG, part).
3. Calls a mock claim-status tool for the claim's current 277-style status (the agent part).
4. Answers in plain language with the source document cited. A person always makes the final call.
