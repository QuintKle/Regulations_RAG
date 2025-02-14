# From Legalese to Tech Specs: A RAG Approach to Summarizing Environmental Regulations for Data Centers

## Overview

This repository accompanies the bachelor thesis **"From Legalese to Tech Specs: A RAG Approach to Summarizing Environmental Regulations for Data Centers"**. 





## Repository Structure
The reprositoy is split up in 
- `RAG` - Contains the core RAG pipeline (retrieval, query rephrasing, generation).
- `Evaluation` - Scripts for retrieval performance analysis and response evaluation.


## Important Notices

- **ISO Document Removal**: ISO standards have been removed due to licensing and copyright restrictions. Users are encouraged to obtain them through official sources.
       
- **API Key Management**: It is recommended to store API keys in a `.env` file to maintain security.
  - Create a `.env` file:
    ```plaintext
    OPENAI_API_KEY=your_api_key_here
    ```
---


## Getting Started

To set up and run the **RAG system**, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/your-username/your-repository.git && cd your-repository
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Set Up Qdrant for Vector Search  
#### Run the script to convert ISO regulatory documents into a structured JSON format:
```bash
 ISO_clean_split_to_json.ipynb
```

#### Run the script to embed processed documents and store them in Qdrant VectorDB:
```bash
 Qdrant_vector_build.ipynb
```

### Ensure `.env` File is Configured
```bash
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

### Run the RAG System
```bash
Presentation showcase.ipynb
```
or
```bash
concept Talk To RAG with memory.ipynb
```
---

#



