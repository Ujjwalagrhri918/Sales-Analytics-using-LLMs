# Sales-Analytics-using-LLMs
 

An automated analytics system that interprets natural language queries and translates them into SQL commands to extract insights from a MySQL-based sales database.

This project utilizes Google PaLM with LangChain to convert user prompts into executable SQL queries. The system leverages few-shot learning, Hugging Face embeddings, and ChromaDB for contextual query understanding and enhanced relevance.

##Key Features
- Converts natural language queries into SQL using LLMs
- Real-time query execution on a structured MySQL database
- Utilizes few-shot learning to guide SQL generation
- Embedding-based retrieval using Hugging Face and ChromaDB
- Scalable architecture for custom database schemas and domains

##Tech Stack
- LLM: Google PaLM (via Generative Language API)
- Orchestration: LangChain with SQLDatabaseChain
- Embeddings: Hugging Face Transformers
- Vector Store: ChromaDB
- Database: MySQL

##How It Works
- User inputs a natural language question.
- Query context is enhanced using few-shot examples and relevant documents retrieved via ChromaDB.
- LangChain uses Google PaLM to convert the query into SQL.
- SQL is executed on the MySQL sales database.
- Result is returned in a readable format.
