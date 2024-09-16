# Web search example

This example demonstrates how to create a chatbot that can use the Tavily search
engine to look up information on the web.

## Running the example

A prerequisite to running this example is to provide your OpenAI and Tavily API keys.

```
export QUARKUS_LANGCHAIN4J_TAVILY_API_KEY=<your-tavily-api-key>
```

Then, simply run the project in Dev mode:

```shell script
./mvnw compile quarkus:dev
```

## Using the example

Open your browser and navigate to http://localhost:8080. Click the red robot
in the bottom right corner to open the chat window.

# quarkus-ai-llm-summarizer

This project uses Quarkus to create a summarizer REST service for test and files. It uses Ollama (llama3.1) LLM in order to do the task.

## Running the application in dev mode

You can run your application in dev mode that enables live coding using:

```shell script
./mvnw compile quarkus:dev
```

## Related Guides

- LangChain4j Ollama ([guide](https://docs.quarkiverse.io/quarkus-langchain4j/dev/index.html)): Provides the basic integration of Ollama with LangChain4j
