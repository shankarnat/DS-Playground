# Implementing a simple RAG

RAG stands for Retrieval Augmented Generation.

Users want to find information and consume them in a concise manner.
They come to AI services such as CHATGPT, which provides concise output but the correctness/accuracy is not guaranteed, because these models are known to hallucinate. 

RAG comes to the rescue, where we augment the prompt to LLMs with context that we retrieve from authoritative sources. This helps LLMs to do their job well and also have the context to avoid any hallucination

Our Simple RAG Prototype
1. User sends few topics as queries to the system
2. System, retrieves authoritative websites, scrapes them and provides it as context to LLM
3. LLM uses this context to provide an exquisite summary.

