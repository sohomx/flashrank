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

ReRanking (example):
Input:
![image](https://github.com/sohomx/flashrank/assets/84140043/00d044f4-75a1-4596-bb25-53162a6a0af2)
Output:
![image](https://github.com/sohomx/flashrank/assets/84140043/2f733e41-0313-410b-899f-431926b9a6c1)

## Code Functionality

This script employs the Flash Rank library to perform re-ranking:
- It uses the Flash Rank's `Ranker` class to rerank search results based on specified queries and passages.
- Users can choose between different model sizes, each offering varied speed and performance characteristics.

## Credits

This script utilizes the Flash Rank library, a lightweight Python library for efficient and effective search result re-ranking based on different model sizes.

-------------------

### Why Flash Rank?

1. Ultra-lightweight Nature: 
Flash Rank stands out for its ultra-lightweight design, operating without the need for Torch or Transformers. Its efficient functionality allows it to run smoothly on CPU. Notably, it boasts the world's smallest reranking model, approximately 4MB in size.

2. Speed and Efficiency:
The re-ranking speed of Flash Rank depends on multiple factors, including the number of tokens in passages, the query length, and the model depth. Its design prioritizes efficiency, offering a balance between speed and performance.

3. Cost-Effective Solutions:
Flash Rank's minimal memory and time requirements make it an ideal choice for cost-effective deployments, particularly for serverless setups like AWS Lambda. This efficiency ensures optimal resource utilization without compromising on performance.

4. Model Variety:
Flash Rank supports a diverse range of models, catering to various needs. This includes models such as the default ms-marco-TinyBERT-L-2-v2, ms-marco-MiniLM-L-12-v2, and more. Additionally, it offers options for multi-lingual support, enhancing its versatility for different applications and languages.
