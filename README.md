# NLP_Semantic_search
Generating Embeddings for an advanced  semantic search engine

# Sentence Embeddings with Sentence Transformer and Qdrant

## Overview
This project demonstrates how to generate sentence embeddings using the Sentence Transformer model "paraphrase-multilingual-MiniLM-L12-v2" and store them in a vector database using Qdrant. Sentence embeddings are numerical representations of sentences that capture their semantic meaning. Qdrant is a vector database that allows efficient similarity search and retrieval of vectors.

## Setup
1. Clone this repository:

2. Install dependencies:

3. Download the Sentence Transformer model:
You can download the "paraphrase-multilingual-MiniLM-L12-v2" model from Hugging Face Transformers (https://huggingface.co/models) or using the `transformers` library.

4. Install and configure Qdrant:
Follow the instructions on the Qdrant documentation (https://qdrant.readthedocs.io/en/latest/) to install and set up the Qdrant vector database.

## Usage
1. Generate Sentence Embeddings and store them in qdrant:
Run the `generating_embeddings.py` script to generate sentence embeddings using the Sentence Transformer model. Update the script with the paths to your data and the downloaded model.
This script has been applied on 6 json files where laws were stored.


3. Test Queries:
Run the `query_test.py` script to demonstrate how to perform similarity search using Qdrant. Modify the script to test your specific queries and requirements.

## Acknowledgments
- This project utilizes the Sentence Transformer library developed by UKPLab (https://github.com/UKPLab/sentence-transformers).
- Qdrant (https://github.com/qdrant/qdrant) is used for efficient similarity search and storage of vector embeddings.

## License
This project is licensed under the [MIT License](LICENSE).

