# Chatbot Applications

This project is a chatbot distributed across several microservices. The chatbot can answer general questions about local dataset that we fine fune

## Services Overview

The project consists of the following services:

1. **Frontend:** A React application providing the user interface for interacting with the chatbot.

2. **Service2:** A Python (FastAPI) backend that coordinates communication between the frontend and Service3. It also manages the interaction history between the user and the chatbot.

3. **Service3:** Another Python (FastAPI) backend hosting the chatbot algorithm. This service communicates with the AI engine (OpenAI GPT-3.5-turbo) to process user queries and generate suitable responses.

4. **Redis:** A Redis server used for state storage across the services, allowing for efficient session management and caching.

5. **Postgres:** A Postgres server acting as a database for storing vector embeddings, enabling enhanced search and retrieval of information.

## Setup Instructions

To get the project up and running, ensure you have Docker installed on your system.



## continue
