# QuerySaurus

Welcome! This project is intended to help people get started thinking about and using LLMs in their programming projects, in particular using local LLMs and vector stores to implement the Retrieval Augmented Generation (RAG) architecture that forms the backbone of many current generative AI applications. It is coded in Python, and uses [Jupyter Notebooks](https://techblog.usnews.com/articles/2017-08-22/making-sense-of-your-data-with-jupyter-notebook) for coding.

## LLaMA 2

We're using LLaMA-based LLMs here, specifically LLMs which are based on the LLaMA 2 foundational model. That model is usable for commercial applications, and is highly capable at things like text summaries.

## Langchain

[LangChain](https://docs.langchain.com/docs/) is the premier framework for building LLM-based applications. It has a vibrant community and is constantly getting better and better.

# Getting Started

## Prerequisites

You need some way to run a local LLM, or you'll need to use a third party LLM such as ChatGPT. The examples in this project use [Ollama](https://ollama.ai/), which only works on Mac OS at the moment (8/31/2023).

**If you are not on Mac OS**, LangChain supports other methods of running local LLMs, such as [Llama.cpp](https://python.langchain.com/docs/integrations/llms/llamacpp), and other LLM classes can be readily substituted in the examples. ChatGPT is quite affordable for small scale projects.

## Installation

* Clone the project using `git`
* Install Python 3.11+
* Create a virtual environment for this project
* Install the requirements
* Run `jupyter lab`
* Open a browser to localhost:8888

# The Notebooks

If you're new to this stuff, the suggested order is:

* LLMs
* Prompting
* Embeddings
* Vector Databases
* Retrieval Augmented Generation (RAG)

# Further Reading and Links

* [Local LLMs with LangChain](https://python.langchain.com/docs/guides/local_llms) - an overview of using local LLMs with LangChain
* [Local retrieval QA](https://python.langchain.com/docs/use_cases/question_answering/how_to/local_retrieval_qa) - more info about what we're doing here with RAG
* [Long term chat memory](https://python.langchain.com/docs/use_cases/question_answering/how_to/chat_vector_db) - using a vector database to implement long term chat memory
* [Ollama Langchain integration](https://python.langchain.com/docs/integrations/chat/ollama)
* [Code understanding with LangChain](https://python.langchain.com/docs/use_cases/code_understanding) - using an LLM to analyze and work with your code
* [Introduction to prompt design](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/introduction-prompt-design) - from Google, but applicable to any LLM
* [LangChain integrations](https://integrations.langchain.com/) - LangChain works with many LLMs, vector databases, other data retrieval sources, and can ingest data from many sources
* [Sentient Silo demo](https://youtu.be/K0S0OwzCwZs) - a demo of some more advanced capabilities in an upcoming side project
