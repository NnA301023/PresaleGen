# PresaleGen 🎯

> An intelligent sales analytics agent powered by natural language processing and machine learning

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)

## 🌟 Overview

PresaleGen is a sophisticated sales analytics tool that leverages natural language processing and machine learning to analyze sales conversations and appointment data. It helps sales teams gain deeper insights into their customer interactions and improve their sales processes.

## ✨ Features

- 🔍 **Historical Sales Analysis**: Process and analyze historical sales appointment data
- 💬 **Conversation Analysis**: Deep dive into sales conversations using advanced NLP
- 🧠 **Intelligent Query Processing**: ReAct agent for handling complex analytical queries
- 📊 **Comprehensive Data Integration**: Combines multiple data sources for holistic analysis
- 🔄 **Context-Aware**: Maintains conversation context for more relevant insights

## 🛠️ Technical Components

- **Query Engine**: Specialized for historical sales appointment data analysis
- **Vector Retriever**: Advanced conversation analysis using vector similarity
- **Gemini LLM**: State-of-the-art language model integration
- **ReAct Agent**: Tool-based reasoning for complex query handling
- **Memory Management**: Efficient conversation context maintenance

## 📋 Requirements

```python
pandas
tiktoken
llama-index
google-generativeai
huggingface-hub
```

## 🚀 Quick Start

```python
from presalegen import SalesAnalyticsAgent

# Initialize the agent
agent = SalesAnalyticsAgent(
    df_appointment=your_appointment_data,
    index=your_vector_index,
    vector_store_info=your_vector_store_info,
    session_id="unique_session_id"
)

# Query the agent
response = agent.query("Show me successful appointments in the tech industry")
```

## 💻 Usage Examples

### Historical Sales Analysis
```python
# Query historical appointment data
result = agent.historical_sales_appointment(
    "What are the top performing campaigns last quarter?"
)
```

### Conversation Analysis
```python
# Analyze sales conversations
insights = agent.conversation_sales_interaction(
    "Find patterns in successful sales calls"
)
```

## 🏗️ Architecture

The SalesAnalyticsAgent consists of several key components:

1. **Query Engine**: Handles structured data analysis
2. **Vector Retriever**: Manages conversation analysis
3. **LLM Integration**: Processes natural language queries
4. **Memory Management**: Maintains conversation context
5. **Tool System**: Coordinates different analytical capabilities

## ⚙️ Configuration

The agent can be configured through the Settings class:

```python
EMBEDDING_NAME = "your_embedding_model"
GEMINI_MODEL_NAME = "your_gemini_model"
GEMINI_API_KEY = "your_api_key"
TEMPERATURE = 0.7
TOKEN_CONVERSATION_LIMIT = 4096
```

## 🔒 Safety Features

- Configurable harm-blocking thresholds
- Token counting and limiting
- Memory management for long conversations
- Customizable safety settings

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the Apache License - see the [LICENSE](https://github.com/NnA301023/PresaleGen/blob/main/LICENSE) file for details.

## 📞 Support

For support, please open an issue in the GitHub repository or contact at my email [here](alif.datascientist@gmail.com).

---

Made with ❤️ by ML Bersatu
