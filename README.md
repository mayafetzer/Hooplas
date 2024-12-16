# Project: Hooplas Mini Basketball Chatbot

## Author
Maya Fetzer, Brandon Roman
Semester: Fall 2024  
Course: CHEG 472  

## Purpose
This repository is meant to hold the machine learning model and chatbot used to answer 
user questions about how to improve their technique to score more points in the mini bowling game at Hooplas. The repository holds the original
as well as the cleaned dataset. Further, the .ipynb file holds a LangChain chatbot that uses an OpenAI api key. 

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
