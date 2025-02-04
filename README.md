# Knowledge-graph-ai

A central hub for company knowledge.A network of interconnected data sources delivering organizational wisdom using RAG with llm.

```
+---------------------------------------------------------+
|                ETL (Data Ingestion) Pipeline            |
|  - Extracts data from multiple, diverse sources         |
|  - Transforms and normalizes data into a unified source  |
|  - Loads data into a centralized repository for further  |
|    processing (i.e., the ontology layer)                |
+---------------------------------------------------------+
                             │
                             ▼
+---------------------------------------------------------+
|          Ontology (Knowledge Graph) Layer               |
|  - Transforms unified data into subject-specific formats|
|  - Creates an ontology/knowledge graph that maps data   |
|    relationships and semantics                          |
+---------------------------------------------------------+
                             │
                             ▼
+---------------------------------------------------------+
|         Vector Embedding Database Layer                 |
|  - Maintains a collection of vector DBs, each focused   |
|    on a specific subject matter                         |
|  - Each DB stores vector representations of domain data |
+---------------------------------------------------------+
                             │
                             ▼
+---------------------------------------------------------+
|      3rd Party AI Tool Integration Layer                |
|  - Integrates with external AI tools                    |
|  - Retrieves meaningful data using:                     |
|       • Knowledge Graph data                            |
|       • Selected Vector Embedding DB results            |
|  - Manages context length & cost constraints            |
+---------------------------------------------------------+
                             │
                             ▼
+---------------------------------------------------------+
|      Query Processing & AI Orchestration Layer          |
|  - Receives user queries                                |
|  - Uses an AI agent to determine the best vector source |
|  - May split the query or delegate to multiple sessions |
+---------------------------------------------------------+
                             │
                             ▼
+---------------------------------------------------------+
|                   User/Client Interface                 |
+---------------------------------------------------------+

```
