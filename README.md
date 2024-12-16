# Project: Hooplas Mini Basketball Chatbot

## Author
Maya Fetzer, Brandon Roman

Semester: Fall 2024  

Course: CHEG 472  

## Purpose
This repository is meant to hold the machine learning model and chatbot used to answer 
user questions about how to improve their technique to score more points in the mini bowling game at Hooplas. The repository holds the original
as well as the cleaned dataset. Further, the .ipynb file holds a LangChain chatbot that uses an OpenAI api key. 

This repository holds the final project for CHEG472, which is a summary of all of the data science and machine learning techniques. The first section of the of the analysis is the data cleaning and exploratory data analysis. The second part of the analysis is testing different machine learning models. The third part is using LangChain and OpenAI to create a chatbot that can process natural language and give recommendations on if the user is above or below the predicted score and how they can improve if they are below. 

## Files in this repository
HooplasAnalysis.ipynb - A file that holds the analysis, ML model, and chatbot for the model
hooplas_dataset - The original dataset collected at Hooplas. 
hooplas_cleaned.csv - A cleaned dataset that is ready for machine learning purposes

## Prerequisites

### Python
Ensure you have Python 3.10 or later installed.

### Libraries
Install the following libraries using pip:

```
!pip install shap -q
!pip install pickle-mixin -q
!pip install numpy -q
!pip install langchain -q
!pip install openai -q
!pip install langchain-community -q
!pip install langchain-openai -q
```

### Explanations

shap:
SHAP (SHapley Additive exPlanations) is a powerful tool for interpreting machine learning models. It helps explain predictions by showing how each feature contributes to the output of the model, based on game-theory principles.

pickle-mixin:
This library is an extension of Python's built-in pickle module, designed to serialize and deserialize Python objects. It's particularly useful for saving and loading complex objects or configurations across different sessions.

numpy:
NumPy is a fundamental library for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, as well as a collection of mathematical functions to operate on them.

langchain:
LangChain is a framework designed to assist in developing language model applications. It provides tools for connecting language models to external data sources, chaining together operations, and building conversational agents and knowledge-based systems.

openai:
This library allows integration with OpenAI's APIs for accessing their language models (like GPT). It is used to query, generate, and process text with state-of-the-art AI models.

langchain-community:
This library provides additional community-driven modules, connectors, and extensions for LangChain, making it easier to integrate with a variety of external tools and APIs.

langchain-openai:
An extension of LangChain specifically designed for seamless integration with OpenAI's language models, combining the power of LangChain's chaining and modularization capabilities with OpenAI's advanced AI features.

