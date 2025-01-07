This project demonstrates the integration of LangChain, Chroma Vector Store, and Gradio to build an interactive conversational AI powered by OpenAI models. It utilizes a retrieval-augmented generation (RAG) pipeline, enabling the system to query a knowledge base and provide insightful answers in a conversational manner.

**Project Overview**
This implementation is designed as an Expert Knowledge Worker, a question-answering agent tailored for employees of Insurellm, an Insurance Tech company. The agent prioritizes accuracy and cost-efficiency, leveraging RAG (Retrieval Augmented Generation) for high-accuracy responses. The first implementation uses a simple, brute-force type of RAG to ensure reliable performance.

**Features**

1.Knowledge Base Integration: Load documents from a directory structure to create a searchable knowledge base.

2.Vector Store: Use Chroma for efficient document chunking and vector embedding storage.

3.Dimensionality Reduction: Visualize document embeddings in 2D and 3D using t-SNE.

4.Interactive Chat: Deploy a chatbot interface using Gradio for seamless interactions.

5.Retrieval-Augmented Generation (RAG): Retrieve contextually relevant chunks from the vector store and generate responses using GPT models.
