## Hi there 👋
# BigDataTeam5 Organization

## Overview

BigDataTeam5 is an organization focused on developing cutting-edge data engineering, AI, and analytics solutions across various domains. Our team specializes in building data pipelines, multi-agent AI architectures, retrieval-augmented generation (RAG) systems, and advanced analytics platforms using modern cloud technologies.

## Our Team

- Shushil Girish
- Yash Khavnekar
- Riya Mate

## Repository Portfolio

### 1. [NVIDIA Agentic Architecture Workflow](https://github.com/BigDataTeam5/Nvidia-Agentic-Architecture-Worflow)

A multi-agent research assistant for NVIDIA financial and corporate analysis using:

- **RAG Agent**: Retrieves historical NVIDIA quarterly reports from Pinecone with metadata filtering
- **Web Search Agent**: Uses SerpAPI for real-time web search related to NVIDIA
- **Snowflake Agent**: Queries structured NVIDIA valuation metrics from Snowflake
- **Architecture**: Multi-node LangGraph orchestration with state management
- **Deployment**: Dockerized FastAPI backend and Streamlit frontend
- **Demo**: [https://nvidia-research-assistant.streamlit.app/](https://nvidia-research-assistant.streamlit.app/)

### 2. [MarketScope AI: Healthcare Product Analytics](https://github.com/BigDataTeam5/MarketScope-AI-Powered-Industry-Segment-Intelligence-Platform)

An intelligent analytics platform for understanding healthcare market segments using advanced AI and NLP:

- **Features**: Market segmentation analysis, strategic query optimization, product comparison, sales & marketing analysis
- **Architecture**: FastAPI backend with MCP servers, Streamlit frontend
- **Healthcare Segments**: Diagnostic, Supplement, OTC Pharmaceutical, Fitness Wearable, Skin Care
- **RAG System**: Provides access to marketing knowledge from Philip Kotler's Marketing Management book
- **Deployment**: Multi-server architecture with unified and specialized microservices

### 3. [Incremental Data Pipeline using Snowflake](https://github.com/BigDataTeam5/Incremental_DataPipleine_using_Snowflake)

A comprehensive data pipeline for processing, analyzing, and visualizing CO2 measurement data using Snowflake:

- **Architecture**: Multi-layer data architecture (Raw, Harmonized, Analytics, External)
- **Key Components**: Raw data ingestion, change data capture, harmonization, analytics processing, UDFs
- **Technologies**: Snowflake, Python, Snowpark, GitHub Actions, AWS S3, AWS Lambda
- **CI/CD Pipeline**: Automated testing and deployment with RSA key-based authentication
- **License**: MIT License

### 4. [Master Financial Database](https://github.com/BigDataTeam5/master-financial-database)

An end-to-end solution for building a master financial statement database for US public companies:

- **Features**: Data scraping, storage design, validation, Airflow ETL pipelines
- **Technologies**: Snowflake, Airflow, dbt, AWS S3, Streamlit, FastAPI
- **Deployment**: Google Cloud Run (FastAPI), Streamlit built-in deployment
- **Demo Application**: Financial analytics dashboard with fundamental analysis capabilities

### 5. [Building a RAG Pipeline with Airflow](https://github.com/BigDataTeam5/Building-a-RAG-Pipeline-with-Airflow)

Enhanced the LLM Extractor Project with RAG concepts for token reduction and improved efficiency:

- **Data Source**: NVIDIA quarterly reports (past 5 years)
- **PDF Parsing Options**: Various parsers including Docling and Mistral OCR
- **RAG Pipeline Options**: Manual embeddings, Pinecone, ChromaDB
- **Chunking Strategies**: Fixed-size, semantic, sliding window
- **Interactive UI**: Streamlit interface with upload, parser selection, query capabilities
- **Deployment**: Dockerized Airflow pipeline and Streamlit + FastAPI interface
- **Demo**: [https://rag-llm-pipelines.streamlit.app/](https://rag-llm-pipelines.streamlit.app/)

### 6. [LiteLLM Summary Generator with Q&A](https://github.com/BigDataTeam5/LiteLLM_SummaryGenerator_with_Q-A)

A Streamlit web application that leverages LLMs for document summarization and question answering:

- **Features**: PDF content selection/upload, LLM-based summarization, question answering
- **Technologies**: Streamlit (frontend), FastAPI (backend), LiteLLM (LLM integrations)
- **Supported LLMs**: GPT-4o, Gemini Flash, DeepSeek, Claude, Grok
- **Architecture**: Redis streams for communication between services
- **Deployment**: Docker Compose, cloud deployment
- **Demo**: [https://llm-interactor-gpt.streamlit.app/](https://llm-interactor-gpt.streamlit.app/)

### 7. [Multi-Agentic Hackathon Project: Crime Analysis](https://github.com/BigDataTeam5/Mulit-Agentic-Hackthon-Project)

A multi-agent research assistant for crime data analysis:

- **Agents**: RAG agent (Pinecone), Web Search agent (SerpAPI), Snowflake agent, ImageGenerator agent, Comparison agent
- **Architecture**: State management with CrimeGPTState, multi-node structure
- **Data Processing**: Input processing, parallel data collection, analysis integration, report generation
- **Technologies**: Python, Pinecone, Snowflake, SerpAPI, Claude 3, Graphviz
- **Deployment**: FastAPI and Streamlit deployments
- **Demo**: [https://crime-analysis-report.streamlit.app/](https://crime-analysis-report.streamlit.app/)

## Technologies Used

### Cloud Services
- **AWS**: S3, Lambda
- **Google Cloud**: Cloud Run
- **Snowflake**: Data warehousing, analytics

### Data & AI
- **Vector Databases**: Pinecone, ChromaDB
- **LLMs**: Claude 3, GPT-4o, Gemini, DeepSeek, Grok
- **RAG Frameworks**: Custom implementations with various embedding strategies

### Development & Deployment
- **Languages**: Python
- **API Frameworks**: FastAPI
- **UI Frameworks**: Streamlit
- **Orchestration**: Apache Airflow, LangGraph
- **Containerization**: Docker, Docker Compose
- **CI/CD**: GitHub Actions

### Search & Extraction
- **Web Search**: SerpAPI
- **PDF Processing**: Docling, Mistral OCR, various parsers

## Getting Started

Each repository has detailed setup instructions in its respective README file. Generally, the process involves:

1. Cloning the desired repository
2. Setting up environment variables 
3. Installing dependencies via pip or Poetry
4. Running the application (typically involves a FastAPI backend and Streamlit frontend)

## Connect With Us

For more information about our projects, please feel free to explore the individual repositories and their documentation.

## License

Most repositories are under MIT License unless otherwise specified.
