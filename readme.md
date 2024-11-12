# NÄGELE AI RAG Application

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Features in Detail](#features-in-detail)
- [Security Considerations](#security-considerations)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Overview
A Streamlit-based chat application that integrates with various LLM providers (OpenAI, Anthropic, Azure OpenAI) and includes RAG (Retrieval-Augmented Generation) capabilities. This application provides an intuitive interface for interacting with different language models while supporting document-based context enhancement.

## Features
- 🤖 Multiple LLM Support:
  - OpenAI models
  - Anthropic Claude models
  - Azure OpenAI integration
- 📚 RAG (Retrieval-Augmented Generation) capabilities
- 📄 Document Upload Support:
  - PDF
  - TXT
  - DOCX
  - MD
- 🌐 URL Content Integration
- 💬 Interactive Chat Interface
- 🔄 Streaming Responses

## Requirements
- Python 3.8+
- Streamlit
- LangChain
- Required API keys:
  - OpenAI API key
  - Anthropic API key (optional)
  - Azure OpenAI credentials (optional)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/arad1367/RAG_Azure_Solution.git
cd RAG_Azure_Solution
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your API keys:
```env
OPENAI_API_KEY=your_openai_key_here
ANTHROPIC_API_KEY=your_anthropic_key_here
# For Azure OpenAI
AZ_OPENAI_API_KEY=your_azure_key_here
AZ_OPENAI_ENDPOINT=your_azure_endpoint_here
```

## Usage
Run the Streamlit application:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501`

## Configuration
The application can be configured through:
- Environment variables in `.env` file
- Streamlit's configuration options
- Model selection in the sidebar
- RAG functionality toggle

## Features in Detail

### Model Selection
- Choose between different LLM providers and models
- Configurable temperature and streaming settings

### RAG Integration
- Upload documents for context-aware responses
- Add URLs for web content integration
- View loaded documents in the sidebar

### Chat Interface
- Clean and intuitive UI
- Real-time streaming responses
- Chat history maintenance
- Clear chat functionality

## Security Considerations
- Store API keys securely in environment variables
- Never commit `.env` file to version control
- Implement appropriate access controls
- Review uploaded documents for security risks

## Troubleshooting
Common issues and solutions:
- API key errors: Ensure proper key format in `.env` file
- Document upload issues: Check file format compatibility
- Connection errors: Verify internet connectivity
- Model availability: Confirm API subscription status

## Contributing
Any contribution is appreciated.

## Acknowledgments
This project is based on the original code by [Enric Domingo](https://github.com/enricd).

## Contact
Feel free to contact me: [Pejman Ebrahimi](https://github.com/arad1367) [`pejman.ebrahimi@uni.li`] & [`pejman.ebrahimi77@gmail.com`]