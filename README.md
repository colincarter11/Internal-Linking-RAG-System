# Internal Link Generator (RAG System)

This project is an AI-powered internal link suggestion tool built with a Retrieval-Augmented Generation (RAG) architecture. It uses OpenAI's language models, LangChain, and Pinecone to semantically understand content and suggest relevant internal links for SEO purposes.

## Features

- Ingests and embeds content using vector embeddings
- Queries documents based on content relevance
- Generates link suggestions using OpenAI's GPT models
- Supports internal SEO workflows for content teams

## Technologies Used

- Python
- OpenAI API
- LangChain
- Pinecone
- (Originally developed in Jupyter, now converted to .py)

## Setup

1. Clone the repo
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Add your API keys for OpenAI and Pinecone
4. Run the script:
    ```bash
    python internal_link_generator.py
    ```

## Notes

- This script was originally prototyped in Jupyter Notebook and converted for GitHub
- Ideal for SEO teams, agencies, or developers building content optimization tools

## License

MIT
