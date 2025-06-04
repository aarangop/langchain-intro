# LangChain Introduction - Building Chatbots

This repository contains examples and tutorials for building conversational AI
applications with LangChain and Anthropic's Claude models.

## Overview

This project demonstrates how to create chatbots with memory, context awareness,
and custom personalities using LangChain's modular components.

## Key Concepts Covered

### Language Model Integration

- Using Anthropic's Claude 3.5 Sonnet model with LangChain
- Working with the LangChain Runnable interface

### Conversation State Management

- Creating stateful conversations with message history
- Supporting multiple conversation threads with unique IDs
- Persisting conversations using MemorySaver

### Prompt Engineering

- Using ChatPromptTemplate to structure model inputs
- Incorporating system messages for personality customization
- Working with MessagesPlaceholders for dynamic content

### Advanced Message Handling

- Managing conversation history size to prevent context window overflow
- Trimming message history while preserving important context
- Working with different message types (Human, AI, System)

### State Management with StateGraph

- Creating workflow graphs for more complex applications
- Defining custom state schemas and message flows
- Implementing async processing for better performance

### Streaming Responses

- Using streaming mode to process chunks of model output
- Filtering and handling streamed content

## Getting Started

1. Ensure you have the required dependencies:

```
pip install -r requirements.txt
```

2. Set up your `.env` file with your Anthropic API key:

```
ANTHROPIC_API_KEY=your_api_key_here
```

3. Open the `chatbot.ipynb` notebook to explore the examples

## Example Usage

The notebook demonstrates how to:

- Create basic and advanced conversational agents
- Customize chatbot personalities and languages
- Maintain conversation context across multiple interactions
- Handle long message histories efficiently
- Stream model responses for interactive applications

## References

- [LangChain Documentation](https://python.langchain.com/docs/)
- [Anthropic Claude API](https://docs.anthropic.com/claude/reference/getting-started-with-claude)
