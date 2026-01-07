## 📈 RAG Project: Financial Analysis of Publicly Traded Companies
This project implements a Retrieval-Augmented Generation (RAG) system designed for in-depth financial analysis of publicly available company reports. Leveraging Large Language Models (LLMs) and vector databases, it provides insightful summaries and evaluations based on value investing principles.

<img width="2000" height="1126" alt="image" src="https://github.com/user-attachments/assets/0f354ead-612e-467b-b35d-23418cc2e7ac" />

## 🔍 Key Features
- <b>Intelligent Document Ingestion:</b> Automatically loads and processes PDF financial reports, detecting fiscal years and quarterly periods.
- <b>Advanced Text Preprocessing:</b> Cleans and optimizes document text for improved retrieval accuracy.
- <b>Contextualized Retrieval:</b> Utilizes similarity search with dynamic metadata filtering (year, quarter) to fetch highly relevant document chunks.
- <b>Persistent Vector Database:</b> Employs ChromaDB for efficient storage and retrieval of document embeddings, ensuring data persistence.
- <b>LLM-Powered Classification:</b> Uses LLMs to classify report years and quarterly periods from both documents and user queries.
- <b>LangChain Expression Language (LCEL):</b> Builds robust and efficient RAG chains for seamless integration of components.
- <b>Prompt Engineering:</b> Crafts specialized prompts for financial analysis, guiding LLMs to provide structured, principled responses.
- <b>Interactive Interface:</b> Offers a Gradio ChatInterface for an intuitive conversational experience.
- <b>Value Investing Framework:</b> Incorporates principles from Warren Buffett, Peter Lynch, and Benjamin Graham for company evaluation.

## 👨‍💻 Technologies
<div style="display: inline_block"><br>
<img align="center" alt="Python" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
<img align="center" alt="LangChain" height="40" width="40" src="https://github.com/user-attachments/assets/340be7a0-4d46-4119-b86c-6f4f3da05c6f" />
<img align="center" alt="OpenAI" height="40" width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/ChatGPT-Logo.svg/1024px-ChatGPT-Logo.svg.png"> 
<img align="center" alt="ChromaDB" height="40" width="40" src="https://github.com/user-attachments/assets/a44c940f-5ec7-4f37-af19-f44f30c6fbd5" />
<img align="center" alt="Gradio" height="40" width="40" src="https://github.com/user-attachments/assets/d3aa941e-3e5f-4688-bec0-80d28b7d07e4" />
<img align="center" alt="PDF" height="40" width="40" src="https://github.com/user-attachments/assets/50a7fba0-b610-4adb-bf46-6c6ef1afc87d" />
</div>

## 📋 Prerequisites 
- Python 3.9+
- OpenAI API Key
- ChromaDB API Key and Tenant ID (for Chroma Cloud)
- Google Colab environment (recommended for seamless execution)

## 🌟 Additional Resources
[Course Certificate](https://certificate.codeforall.com/verify/24df640315965?s)<br>
[LangChain Documentation](https://docs.langchain.com/oss/python/langchain/overview)<br>
[ChromaDB Documentation](https://docs.trychroma.com/docs/overview/introduction)<br>
[OpenAI API Documentation](https://platform.openai.com/docs/overview)<br>
