# Automatic Question Generator

## Overview
This project involves the development of an Automatic Question Generator using Python. 
It leverages the ChatGPT 3.5 OpenAI API, along with other libraries, to create a system capable of generating questions from provided text. 
This can be particularly useful in educational settings, content creation, and various other applications where automated question generation is required.

## Requirements
- Python 3.6 or later
- OpenAI API Key
- Various Python libraries including `langchain`, `openai`, `pypdf`, and `faiss-cpu`

## Installation
Run the following command to install the required packages:

```bash
!pip install langchain openai pypdf faiss-cpu

## Configuration
OpenAI API Key: You need to obtain an API key from OpenAI. Set this key in your environment variables or within your application to authenticate your requests.
Python Environment: Ensure Python 3.6 or later is installed on your machine. It's recommended to use a virtual environment.

# Usage
1. Import Libraries: Import necessary libraries in your Python script.

   ```python
    import openai
    import langchain
    other imports as necessary

3. API Setup: Configure the OpenAI API with your API key.
   
   ```python
   openai.api_key = 'your-api-key'

5. Question Generation: Implement the logic to generate questions from the text. You can use langchain and OpenAI's GPT-3.5 model for this purpose.

6. PDF Processing (Optional): If you are processing PDFs, use pypdf to extract text.

7. Advanced Features: Implement advanced features like indexing, searching, or similarity checks using faiss-cpu if needed.

# Examples
Provide examples of how to use your script to generate questions, including how to input text and interpret the output.

# Limitations and Known Issues

**API Dependency**: The system relies on the OpenAI API, which may have usage limits or costs associated with it.
**Quality of Questions**: The quality of generated questions may vary based on the input text and the model's current capabilities.
**Language Support**: Depending on the model's training, some languages might be better supported than others.

# Contributing
Guide potential contributors on how they can help with the project. This could include instructions for forking the repository, making changes, and submitting pull requests.
