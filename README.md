# LangGraph Chatbot – Research & Knowledge Assistant

This repository contains a simple yet powerful chatbot built using LangGraph, integrated with various research and information tools like ArXiv, Wikipedia, and Tavily. The bot is powered by Groq’s Qwen QWQ-32B model and can handle both general and academic queries with ease.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Tools and Technologies](#tools-and-technologies)

## Introduction

This chatbot is built using LangGraph – a graph-based orchestration framework for LLM workflows. It intelligently routes user queries through appropriate tools like:

- Wikipedia (for general knowledge)

- ArXiv (for academic paper search)

- Tavily (for web-based insights)

These tools, combined with ChatGroq (Qwen-QWQ-32B), create a conversational AI that is both research-aware and highly performant.

## Features

- 🔍 Academic Research with ArXiv

- 🌐 General Knowledge Lookup via Wikipedia

- 🌎 Real-time web results from Tavily

- 🧠 Powerful LLM response engine with ChatGroq

- 🔄 LangGraph-based graph logic for flexible tool routing

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/LangGraph-Chatbot---Research-Knowledge-Assistant.git
```

2. Navigate to the project directory:

```
   cd LangGraph-Chatbot---Research-Knowledge-Assistant
```

3. Install the required dependencies:

```
   pip install -r requirements.txt
```

4. Set up environment variables by creating a .env file (Use .env.sample as a reference for setting up your .env file.)

## Usage

- Run the Jupyter Notebook:

```
   jupyter notebook langgraph.ipynb
```

## Tools and Technologies

- LangGraph – Graph orchestration for LLM workflows

- LangChain – Tool and agent integrations

- Groq + Qwen-QWQ-32B – Super-fast LLM inference

- ArXiv API – Research paper access

- Wikipedia API – General knowledge

- Tavily API – Real-time web content
