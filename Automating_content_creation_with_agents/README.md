

# Automating Research and Content Creation with Multi-Agent Systems

# Introduction
 This project demonstrates the use of multi-agent systems via the CrewAI framework to automate the process of generating insightful and engaging articles.

We utilize the Groq language model and DuckDuckGo search to create three specialized agents: a researcher to analyze the latest advancements, a writer to craft a compelling article, and an editor to refine the content. This approach showcases the potential of AI to streamline the entire content creation process, making it faster and more efficient.


Follow along as we set up and execute this multi-agent system in a Colab notebook, illustrating a practical application of AI in automating complex tasks.


## Installation

To install the required packages, run:

```bash
pip install langchain langchain_core langchain_groq crewai duckduckgo-search crewai[tools]
