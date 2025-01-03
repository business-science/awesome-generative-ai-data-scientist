# Awesome Generative AI Data Scientist [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of 50+ resources to help you become a Generative AI Data Scientist. This repository includes resources on building GenAI applications with Large Language Models (LLMs), and deploying LLMs and GenAI with Cloud-based solutions.

**NOTE** - This is a work in progress. So that you know, changes and additions are welcome. Please use Pull Requests to suggest modifications and improvements. 

## Contents:

- [Awesome Real World AI Use Cases](#awesome-real-world-ai-use-cases)
- [Python Libraries](#python-libraries)
- [Examples and Cookbooks](#examples-and-cookbooks)
- [Newsletters](#newsletters)
- [Courses and Training](#courses-and-training)

# Awesome Real-World AI Use Cases

- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps): LLM RAG AI Apps with Step-By-Step Tutorials
- [AI Data Science Team](https://github.com/business-science/ai-data-science-team): An AI-powered data science team of copilots that uses agents to help you perform common data science tasks 10X faster.
- [AI Hedge Fund](https://github.com/virattt/ai-hedge-fund): Proof of concept for an AI-powered hedge fund
- [AI Financial Agent](https://github.com/virattt/ai-financial-agent): A financial agent for investment research

# Python Libraries

## AI LLM Frameworks

- [LangChain](https://www.langchain.com/): A framework for developing applications powered by large language models (LLMs). [Documentation](https://python.langchain.com/) [Github](https://github.com/langchain-ai/langchain) [Cookbook](https://github.com/langchain-ai/langchain/tree/master/cookbook)
- [LangGraph](https://github.com/langchain-ai/langgraph): A library for building stateful, multi-actor applications with LLMs, used to create agent and multi-agent workflows. [Documentation](https://langchain-ai.github.io/langgraph/) [Tutorials](https://github.com/langchain-ai/langgraph/tree/main/docs/docs/tutorials)
- [LlamaIndex](https://www.llamaindex.ai/): LlamaIndex is a framework for building context-augmented generative AI applications with LLMs. [Documentation](https://docs.llamaindex.ai/) [Github](https://github.com/run-llama/llama_index)
- [LlamaIndex Workflows](https://www.llamaindex.ai/blog/introducing-workflows-beta-a-new-way-to-create-complex-ai-applications-with-llamaindex): LlamaIndex workflows is a mechanism for orchestrating actions in the increasingly-complex AI application we see our users building.
- [CrewAI](https://www.crewai.com/): Streamline workflows across industries with powerful AI agents. [Documentation](https://docs.crewai.com/) [Github](https://github.com/crewAIInc/crewAI)
- [AutoGen](https://github.com/microsoft/autogen) - A programming framework for agentic AI by Microsoft.
- [LangFlow](https://www.langflow.org/): A low-code tool that makes building powerful AI agents and workflows that can use any API, model, or database easier. [Documentation](https://docs.langflow.org/) [Github](https://github.com/langflow-ai/langflow)
- [Pydantic AI](https://ai.pydantic.dev/): Python agent framework designed to make it less painful to build production grade applications with Generative AI. [Github](https://github.com/pydantic/pydantic-ai)

## LLM Models and Providers

- [OpenAI](https://github.com/openai/openai-python): The official Python library for the OpenAI API
- [Hugging Face Models](https://huggingface.co/models): Open LLM models by Meta, Mistral, and hundreds of other providers
- [Anthropic Claude](https://github.com/anthropics/anthropic-sdk-python): The official Python library for the Anthropic API
- [Meta Llama Models](https://llama.meta.com/): The open source AI model you can fine-tune, distill and deploy anywhere.
- [Google Gemini](https://github.com/google-gemini/generative-ai-python): The official Python library for the Google Gemini API
- [Ollama](https://github.com/ollama/ollama): Get up and running with large language models locally.
- [Grok](https://github.com/groq/groq-python): The official Python Library for the Groq API

## Huggingface Platform

- [Huggingface](https://huggingface.co/): An open-source platform for machine learning (ML) and artificial intelligence (AI) tools and models.  [Documentation](https://huggingface.co/docs)

## Vector Databases (RAG)

- [ChromaDB](https://github.com/chroma-core/chroma): The fastest way to build Python or JavaScript LLM apps with memory!
- [FAISS](https://github.com/facebookresearch/faiss): A library for efficient similarity search and clustering of dense vectors.
- [Qdrant](https://qdrant.tech/): High-Performance Vector Search at Scale
- [Pinecone](https://github.com/pinecone-io/pinecone-python-client): The official Pinecone Python SDK.
- [Milvus](https://github.com/milvus-io/milvus): Milvus is an open-source vector database built to power embedding similarity search and AI applications. 

## Pretraining

- [PyTorch](https://pytorch.org/) - PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing.
- [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an open source machine learning library developed by Google.
- [JAX](https://github.com/jax-ml/jax) - Google’s library for high-performance computing and automatic differentiation.
- [tinygrad](https://github.com/tinygrad/tinygrad) - A minimalistic deep learning library with a focus on simplicity and educational use, created by George Hotz.
- [micrograd](https://github.com/karpathy/micrograd) - A simple, lightweight autograd engine for educational purposes, created by Andrej Karpathy.


## Fine-tuning

- [Transformers](https://huggingface.co/docs/transformers/en/installation) - Hugging Face Transformers is a popular library for Natural Language Processing (NLP) tasks, including fine-tuning large language models.
- [Unsloth](https://github.com/unslothai/unsloth) - Finetune Llama 3.2, Mistral, Phi-3.5 & Gemma 2-5x faster with 80% less memory!
- [LitGPT](https://github.com/Lightning-AI/litgpt) - 20+ high-performance LLMs with recipes to pretrain, finetune, and deploy at scale.
- [AutoTrain](https://github.com/huggingface/autotrain-advanced) - No code fine-tuning of LLMs and other machine learning tasks.

## Testing and Monitoring

- [Opik](https://github.com/comet-ml/opik) - Opik is an open-source platform for evaluating, testing and monitoring LLM applications

## Document Parsing

- [Embedchain](https://embedchain.ai/): Create an AI app on your own data in a minute [Documentation](https://docs.embedchain.ai/get-started/quickstart) [Github Repo](https://github.com/mem0ai/mem0/tree/main/embedchain)
- [Docling by IBM](https://ds4sd.github.io/docling/): Parse documents and export them to the desired format with ease and speed. [Github](https://github.com/DS4SD/docling)
- [Markitdown by Microsoft](https://github.com/microsoft/markitdown): Python tool for converting files and office documents to Markdown.
- [Gitingest](https://gitingest.com/): Turn any Git repository into a simple text ingest of its codebase. This is useful for feeding a codebase into any LLM. [Github](https://github.com/cyclotruc/gitingest)

## LLM Memory

- [Mem0](https://mem0.ai/): Mem0 is a self-improving memory layer for LLM applications, enabling personalized AI experiences that save costs and delight users. [Documentation](https://docs.mem0.ai/) [Github](https://github.com/mem0ai/mem0)
- [Memary](https://github.com/kingjulio8238/Memary): Open Source Memory Layer For Autonomous Agents

## Miscellaneous

- [AdalFlow](https://github.com/SylphAI-Inc/AdalFlow) - The library to build & auto-optimize LLM applications, from Chatbot, RAG, to Agent by [SylphAI](https://www.sylph.ai/).
- [dspy](https://github.com/stanfordnlp/dspy) - DSPy: The framework for programming—not prompting—foundation models.
- [AutoPrompt](https://github.com/Eladlev/AutoPrompt): A framework for prompt tuning using Intent-based Prompt Calibration.
- [PromptFify](https://github.com/promptslab/Promptify): A library for prompt engineering that simplifies NLP tasks (e.g., NER, classification) using LLMs like GPT.
- [LiteLLM](https://github.com/BerriAI/litellm): Python SDK, Proxy Server (LLM Gateway) to call 100+ LLM APIs in OpenAI format.
- [LLMOps](https://github.com/callmesora/llmops-python-package): Best practices designed to support your LLMOps initiatives
- [Jupyter Agent](https://huggingface.co/spaces/data-agents/jupyter-agent): Let a LLM agent write and execute code inside a notebook
- [Jupyter AI](https://github.com/jupyterlab/jupyter-ai): A generative AI extension for JupyterLab [Documentation](https://jupyter-ai.readthedocs.io/en/latest/)
- [Pyspur](https://github.com/PySpur-Dev/pyspur): Graph-Based Editor for LLM Workflows
- [Browser-Use](https://github.com/browser-use/browser-use): Make websites accessible for AI agents
- [Agenta](https://github.com/Agenta-AI/agenta): Open-source LLMOps platform: prompt playground, prompt management, LLM evaluation, and LLM Observability all in one place. [Documentation](https://docs.agenta.ai/) 


# LLM Deployment (Cloud Services)

- [AWS Bedrock](https://aws.amazon.com/bedrock/): Amazon Bedrock is a fully managed service that offers a choice of high-performing foundation models (FMs) from leading AI companies like AI21 Labs, Anthropic, Cohere, Meta, Mistral AI, Stability AI, and Amazon
- [Microsoft Azure AI Services](https://azure.microsoft.com/en-us/products/ai-services): Azure AI services help developers and organizations rapidly create intelligent, cutting-edge, market-ready, and responsible applications with out-of-the-box and prebuilt and customizable APIs and models. 
- [Google Vertex AI](https://cloud.google.com/vertex-ai): Vertex AI is a fully-managed, unified AI development platform for building and using generative AI.
- [NVIDIA NIM](https://www.nvidia.com/en-us/ai): NVIDIA NIM™, part of NVIDIA AI Enterprise, provides containers to self-host GPU-accelerated inferencing microservices for pretrained and customized AI models across clouds, data centers, and workstations.


# Examples and Cookbooks

## Building AI

- [LangChain Cookbook](https://github.com/langchain-ai/langchain/blob/master/cookbook/README.md): Example code for building applications with LangChain, with an emphasis on more applied and end-to-end examples.
- [LangGraph Examples](https://github.com/langchain-ai/langgraph/tree/main/examples): Example code for building applications with LangGraph
- [Llama Index Examples](https://github.com/run-llama/llama_index/tree/main/docs/docs/examples): Example code for building applications with Llama Index
- [Streamlit LLM Examples](https://github.com/streamlit/llm-examples): Streamlit LLM app examples for getting started

## Deploying AI

### Amazon Web Services (AWS)

- [Azure Generative AI Examples](https://github.com/Azure/azureml-examples/tree/main/sdk/python/generative-ai): Prompt Flow and RAG Examples for use with the Microsoft Azure Cloud platform
- [Amazon Bedrock Workshop](https://github.com/aws-samples/amazon-bedrock-workshop): Introduces how to leverage foundation models (FMs) through Amazon Bedrock

### Microsoft Azure

- [Microsoft Generative AI for Beginners](https://microsoft.github.io/generative-ai-for-beginners/#/) 21 Lessons teaching everything you need to know to start building Generative AI applications [Github](https://github.com/microsoft/generative-ai-for-beginners)
- [Microsoft Intro to Generative AI Course](https://learn.microsoft.com/en-us/training/paths/introduction-generative-ai/) 

### Google Cloud Platform (GCP)

- [Google Vertex AI Examples](https://github.com/GoogleCloudPlatform/vertex-ai-samples): Notebooks, code samples, sample apps, and other resources that demonstrate how to use, develop and manage machine learning and generative AI workflows using Google Cloud Vertex AI
- [Google Generative AI Examples](https://github.com/GoogleCloudPlatform/generative-ai): Sample code and notebooks for Generative AI on Google Cloud, with Gemini on Vertex AI

### NVIDIA 

- [NVIDIA NIM Anywhere](https://github.com/NVIDIA/nim-anywhere): An entry point for developing with NIMs that natively scales out to full-sized labs and up to production environments.
- [NVIDIA NIM Deploy](https://github.com/NVIDIA/nim-deploy): Reference implementations, example documents, and architecture guides that can be used as a starting point to deploy multiple NIMs and other NVIDIA microservices into Kubernetes and other production deployment environments.

# Newsletters

- [Python AI/ML Tips](https://github.com/business-science/free-ai-tips) - Free newsletter on Generative AI and Data Science.
- [unwind ai](https://www.theunwindai.com/) - Latest AI news, tools, and tutorials for AI Developers

# Courses and Training

## Free Training

- [Generative AI Data Scientist Workshops](https://learn.business-science.io/ai-register) Get free training on how to build and deploy Generative AI / ML Solutions. [Register for the next free workshop here.](https://learn.business-science.io/ai-register)

## Paid Courses

- [8-Week AI Bootcamp by Business Science](https://learn.business-science.io/generative-ai-bootcamp-enroll): Focused on helping you become a Generative AI Data Scientist. Learn How To Build and Deploy AI-Powered Data Science Solutions using LangChain, LangGraph, Pandas, Scikit Learn, Streamlit, AWS, Bedrock, and EC2.
