## RAG Workflow with n8n

This repository hosts an Agentic Retrieval-Augmented Generation (RAG) workflow built using n8n, designed to provide information from machine learning-related documents stored in Google Drive.  <br>

The workflow leverages Pinecone as a vector database, OpenAI Text Embeddings 3 Small for embedding generation, LLaMA3 70B-8192 (via Groq) as the primary LLM, and Gemini 1.5 Flash for validating and reasoning over vector store queries. 
The system uses simple storage for context retention and automatically updates the Pinecone database when documents are added or modified in Google Drive.

feel free to copy the JSON workflow and add your own API credentials.

![image](images/image.png)

![image](images/image-vectorization.png)

See it in action here: https://drive.google.com/file/d/1CS0g856ZWGD2MeZp8XA3M0F3zE0zNL9v/view?usp=sharing


Tools used

[![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://www.google.com/drive/)
[![Pinecone](https://img.shields.io/badge/Pinecone-00C4B4?style=for-the-badge&logo=pinecone&logoColor=white)](https://www.pinecone.io/)
[![OpenAI Embeddings](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://www.openai.com/)
[![Groq](https://img.shields.io/badge/Groq-FF6C37?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com/)
[![Gemini](https://img.shields.io/badge/Gemini-34A853?style=for-the-badge&logo=google&logoColor=white)](https://gemini.google.com/)
[![n8n](https://img.shields.io/badge/n8n-FF5733?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/)



---
Made with ❤️ by [Subhanu](https://github.com/subhanu-dev)
