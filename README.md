# Enhancing Document Interaction with LangChain VectorStore Retrievals
This repository has a script demonstrating how two of LangChain's VectorStore retrievals algorithms work. Retrievers are a great tool for efficient document retrieval and prioritization, and here we try to showcase these two functionalities!

## Retrievers
- **Similarity Search:** Finds documents similar to a given query by comparing their similarities.
- **Maximal Marginal Relevance (MMR):** Prioritizes diverse and relevant documents in search results.

## Setup
1. Create a virtual enviroment
```
python3 -m venv .venv   
source .venv/bin/activate
```
2. Install dependecies
```
pip install -r requirements.txt
```
3. Set up OpenAPI key
```
# On a .env file:
OPENAI_API_KEY=your_key
```
4. Run the script!
```
python3 langchain_retriever_texts.py
```
Don't forget to have fun! Play around with the queries, add more text into the database!

## Acknowledgment
This blog post was inspired by the insights and knowledge gained from the LangChain: Chat with Your Data course offered by deeplearning.ai.

### Happy coding!
