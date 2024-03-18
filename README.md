# RAG-based text documents Q&A chat with LangChain and ChatGPT 

RAG stands for retrieval augmented generation and it works by retrieving external documents and using them when executing queries to the LLMs. Using this technique we can ask out language model questions specific for the content of these documents. We will build a simple demo of it where the LLM will answer some questions regarding the set of external text files.

We'll use Stanford's CS224 Natural Language Processing with Deep Learning amazing course's syllabus and lectures trascript text files as our external data content we want to ask questions about.

In this experiment I used:
* Data source: text files
* Embeddings: OpenAIEmbeddings
* Model: gpt-3.5-turbo
* RAG: LangChain
