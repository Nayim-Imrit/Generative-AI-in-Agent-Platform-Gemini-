# Gemini API with Vertex AI – Function Calling & Multimodal AI

This repository contains a collection of Jupyter notebooks demonstrating how to use Google's Gemini models with the Vertex AI Gemini API. The notebooks cover function calling, multimodal AI, and an end-to-end challenge using the Google Gen AI SDK.

## 📚 Project Overview

The purpose of this project is to explore the capabilities of the Gemini API, including:

- Function Calling
- Tool Integration
- Multimodal AI (Text, Images, and Video)
- Prompt Engineering
- Streaming Responses
- Vertex AI Gemini SDK

---

## 📂 Project Structure

```
.
├── intro_function_calling.ipynb
├── intro_Gemini_multimodal_use_cases.ipynb
├── gemini-explorer-challenge.ipynb
└── README.md
```

---

## 📖 Notebooks

### 1. intro_function_calling.ipynb

Demonstrates how Gemini can call external functions (tools) instead of generating plain text.

Topics covered:

- Creating `FunctionDeclaration`
- Creating `Tool` objects
- Passing tools to Gemini
- Automatic function calling
- Weather function example
- Configuring `GenerateContentConfig`

---

### 2. intro_Gemini_multimodal_use_cases.ipynb

Explores Gemini's multimodal capabilities by processing different input types.

Topics covered:

- Text generation
- Image understanding
- Video analysis
- Loading media using `Part.from_uri()`
- Streaming model responses
- Gemini Flash multimodal model

Example:

- Describe a Mediterranean Sea video
- Recommend similar travel destinations
- Explain visual content

---

### 3. gemini-explorer-challenge.ipynb

A practical challenge that combines the concepts learned throughout the labs.

Topics include:

- Prompt engineering
- Gemini model interaction
- Function calling
- Multimodal reasoning
- Real-world AI application development

---

## 🚀 Technologies Used

- Python 3.x
- Google Gen AI SDK
- Vertex AI Gemini API
- Jupyter Notebook
- Google Cloud Platform

---

## 🧠 Gemini Models

This project demonstrates the use of:

- Gemini Flash
  - Fast inference
  - Low latency
  - Cost efficient
  - Multimodal support

---

## 📦 Installation

Install the required dependencies:

```bash
pip install google-genai
pip install vertexai
pip install nest_asyncio
```

Authenticate with Google Cloud before running the notebooks.

---

## 📌 Learning Outcomes

After completing these notebooks, you will understand how to:

- Use the Google Gen AI SDK
- Interact with Gemini models
- Build AI applications using function calling
- Create tools that Gemini can invoke
- Analyze videos and images using multimodal models
- Stream responses from Gemini
- Integrate external APIs with Gemini

---

## 📖 References

- Vertex AI Gemini Documentation
  - https://cloud.google.com/vertex-ai/docs/generative-ai

- Function Calling
  - https://cloud.google.com/vertex-ai/generative-ai/docs/model-reference/function-calling

- Gemini SDK
  - https://cloud.google.com/vertex-ai/docs/generative-ai/multimodal/sdk-for-gemini

- Google Gen AI SDK
  - https://googleapis.github.io/python-genai/

---

## 👤 Author

Created as part of Google Cloud Vertex AI Gemini hands-on labs and learning exercises.
