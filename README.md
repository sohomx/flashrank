## Usage

This Python script uses the Flash Rank library to perform search and retrieval re-ranking based on various model sizes. It's a Streamlit app designed for efficient re-ranking of search results using different model sizes.

### Steps:

1. **Model Selection:**
    - Choose a model size from options: Nano, Small, Medium, or Large.
    - Each model offers different performance and size characteristics.

2. **About Flash Rank:**
    - Explore information about Flash Rank, its lightweight nature, and its effectiveness for search and retrieval reranking.

3. **Input Query and Context:**
    - Enter a query in the "Query Input" field.
    - Input context or passages related to the query in the "Context Input" field.

4. **ReRanking:**
    - Click the "ReRank" button to process the query and context through the chosen Flash Rank model.
    - Results will display below, showcasing the re-ranked output based on the selected model size.

## Code Functionality

This script employs the Flash Rank library to perform re-ranking:
- It uses the Flash Rank's `Ranker` class to rerank search results based on specified queries and passages.
- Users can choose between different model sizes, each offering varied speed and performance characteristics.

## Credits

This script utilizes the Flash Rank library, a lightweight Python library for efficient and effective search result re-ranking based on different model sizes.
