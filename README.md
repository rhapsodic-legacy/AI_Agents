# Agents
## From First Steps to Advanced Use Cases 

### Purpose
This repository is designed for university students learning to build AI agents using **LangChain**, a powerful Python framework for creating intelligent agents. The goal is to guide students from their **first simple agent** to **advanced agentic use cases**, such as task automation, web scraping, data analysis, and more. Each agent in this series builds on the previous one, introducing new concepts, tools, and real-world applications in a student-friendly, hands-on way. 

Whether you're a beginner or advancing toward complex projects, this repo provides code, tutorials, and insights to help you master AI agent development.

### Contents
The repository currently includes two folders, with more to be added as the series expands:
 
- **A_Langchain_Simple**: The starting point for your AI agent journey.
  - `first_agent.ipynb`: A Google Colab notebook containing a simple but functional AI agent built with LangChain and Google’s Gemini 1.5 Flash (free tier). This agent uses a calculator tool to solve math queries, like "What is 5 + 3 * 2?".
  - `building_your_first_agent.txt`: A detailed, student-friendly tutorial covering:
    - What an AI agent is.
    - How to set up your environment and obtain a Gemini API key.
    - A step-by-step walkthrough of the agent code.
    - Tips for optimizing free-tier usage to stay within API limits.

- **B_Langchain_Expanded**: Multi-Tool AI Agent
  - Expands on A_Langchain_Simple with a versatile agent using Gemini 1.5 Flash (free tier).  
  - langchain_expanded.ipynb: Google Colab notebook with an agent integrating three tools: calculator (math queries), DuckDuckGo web search (e.g., Python tutorials), and file reader (local text files). Includes memory and verbose output.
  - example.txt: Sample file for the file reader tool.
  - walkthrough.txt: Student-friendly guide explaining the code, tools, and next steps.
 
- **C_Langchain_ReAct**: Advanced ReAct-based AI Agent with Multiple Tools
  - This folder is designed for students ready to explore advanced agent architectures, understanding how reasoning frameworks and multiple tools can be leveraged to tackle complex, real-world problems.
  - Advances the series by introducing the ReAct (Reasoning and Acting) framework, enabling the agent to reason about its actions and use tools more effectively.
  - C_Langchain_ReAct.ipynb: Google Colab notebook featuring an agent built with LangChain and Gemini 1.5 Flash (free tier). The agent integrates a variety of tools for tasks such as  mathematical calculations, web searches, file operations, and data processing, while using memory for contextual awareness.
  - conversation_log.json: Demonstrates memory usage by logging interactions.
  - walkthrough.txt: Comprehensive tutorial explaining the ReAct framework, tool integration, memory management, and strategies for managing API quotas.
  - test_output.txt and example.txt: Files for practical testing and demonstrations.

**D_AutoGPT_Basic**: Simplified AutoGPT for Python Task Automation
  - Introduces an alternative approach to task automation with a static, beginner-friendly AutoGPT-like agent for Python tasks, focusing on data analysis.
  - Complements the LangChain agents by demonstrating a different method for automating workflows.
  - auto_gpt_data_analysis.ipynb: AI agent breaks down objectives, generates and executes predefined Python code, and manages the process without external API dependencies.
  - walkthrough.txt: Detailed tutorial for hands-on learning. 

Future folders will include more advanced agents, such as those integrating web APIs, memory, or multi-tool workflows.


### License
This project is licensed under the **MIT License**. 

---

**MIT License**

Copyright (c) 2025 Rhapsodic Legacy

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
