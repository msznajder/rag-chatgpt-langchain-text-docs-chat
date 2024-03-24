# RAG-based text documents Q&A chat using Mistral 7B, ChatGPT and LangChain

## Introduction
I have built a simple RAG demo where the LLM answers questions regarding the set of external text files. RAG stands for retrieval augmented generation. It works by retrieving external documents and using them when executing queries to the LLMs. Text files served as input data and two LLMs to compare their performance: commercial ChatGPT API and open-source Mistral 7B. Finally LangChain was used to connect it all into a RAG application.

We'll use Stanford's CS224 Natural Language Processing with Deep Learning amazing course's syllabus and lectures trascript text files as our external data content we want to ask questions about.

In this experiment I used:
* Data source: text files
* Model 1: gpt-3.5-turbo with OpenAIEmbeddings embeddings
* Model 2: Mistral 7B with e5-large embeddings
* RAG: LangChain
