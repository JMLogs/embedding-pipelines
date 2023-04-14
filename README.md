# Build a real-time financial news chatbot with Bytewax, Langchain, Redis and Openai


>*Powered by [Bytewax](https://bytewax.io/), [Redis](https://redis.io), [LangChain](https://python.langchain.com/en/latest/), and [OpenAI](https://platform.openai.com)*

This tutorial is based off of the Redis/Langchain tutorial that created a conversational retail shopping assistant to help customers find items of interest that are buried in a product catalog. Instead of looking for products, we are going to make this chatbot help us better understand the news.

As the original authors did, I would encourage you to try various prompt-engineering techniques to improve on this prototype for your use case! or to add additional news sources to the pipeline.

## Getting Started

1. [Get an OpenAI API Key](https://platform.openai.com).
2. Add the API key to the [`docker-compose.yml`](./docker-compose.yml) file here in the repo.
3. Start up the docker compose environment:
    ```bash
    docker compose up
    ```

## Coming Soon

- Extensions to LangChain + Redis integration for conversational memory storage
- Have an idea or contribution to make this even better? Open an issue -- let's collaborate!
