# Autogen Multi-agent Conversation and Recall using Memori

This repository contains a Jupyter Notebook demonstrating how to create memory-enhanced [Autogen](https://github.com/microsoft/autogen) AI agents using the **[Memori](https://github.com/GibsonAI/memori)** memory engine. The example builds a consulting team of AI agents that can remember and build upon past conversations, making interactions more intelligent and context-aware.

## Features
- **Persistent Memory**: Agents remember conversations across sessions.
- **Multi-agent Collaboration**: AI agents work together to solve client problems.
- **Real-world Scenario**: Simulates a software consulting team assisting a client.

## Getting Started
1. Install the required dependencies:
   ```bash
   pip install memorisdk autogen-agentchat "autogen-ext[openai]" python-dotenv
   ```
2. Set up your OpenAI API key:
   - As an environment variable: `export OPENAI_API_KEY="sk-your-key-here"`
   - Or in a `.env` file: `OPENAI_API_KEY=sk-your-key-here`

3. Open the notebook `agentchat_groupchat_memory_using_memori.ipynb` and follow the steps to:
   - Initialize the memory system.
   - Create AI agents with distinct roles.
   - Simulate client conversations.

## Use Cases
- Customer Support
- Project Management
- Educational Tutoring
- Medical Consultation

## Learn More
Explore the notebook to see how **Memori** enables smarter, memory-enhanced AI interactions.

