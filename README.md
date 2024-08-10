# Azure Restaurant ChatBot

using https://learn.microsoft.com/en-us/training/modules/use-own-data-azure-openai/


Welcome to the Restaurant AI Bot project! This AI-powered bot is designed to enhance the dining experience by providing intelligent recommendations and detailed information about dishes on a restaurant's menu. Whether you're looking for dishes with specific ingredients, seeking meals within a certain price range, or simply exploring the menu, this bot is here to assist you.

## Project Overview
The Restaurant AI Bot leverages advanced data processing techniques and Retrieval Augmented Generation (RAG) with Azure OpenAI Service to deliver accurate and personalized responses to user queries. By parsing structured data from a menu file, the bot can filter dishes based on various criteria such as ingredients, price, nutritional content, and more.

## Key Features
Ingredient-Based Recommendations: Users can input specific ingredients they desire in a dish, and the bot will recommend menu items that contain those ingredients.
Price Filtering: The bot can suggest dishes that fit within a user-defined budget, ensuring affordable dining options.
Detailed Nutritional Information: For health-conscious diners, the bot can provide comprehensive nutritional details about each dish, including calories, fat content, sugar levels, and more.
RAG Integration: By integrating RAG with Azure OpenAI, the bot can retrieve relevant sections of the menu data and generate human-like responses to user queries.
User-Friendly Interface: Built using Streamlit, the bot offers a simple and intuitive interface, making it easy for users to interact and get the information they need.
How It Works
Data Parsing: The bot processes a structured JSON file containing detailed information about each dish, including ingredients, price, nutritional data, preparation steps, and tags.
Query Handling: Users can input queries such as "recommend dishes with chicken and under $10." The bot then filters the menu based on the provided criteria.
RAG-Driven Responses: For more complex queries, the bot uses Retrieval Augmented Generation to pull relevant data and generate detailed responses.