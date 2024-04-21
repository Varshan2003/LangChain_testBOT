# LangChain Test BOT

LangChain Test BOT is a Streamlit-based application that utilizes LangChain Core and Community libraries to provide assistance in answering user queries.

## Description

This application serves as a demonstration of how to integrate LangChain's language processing capabilities into a Streamlit application. It leverages the LangChain Core and Community libraries to generate responses to user queries using a language model.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Varshan2003/LangChain_testBOT.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the required environment variables set up:

    - `LANGCHAIN_API_KEY`: Your LangChain API key.
    - `LANGCHAIN_TRACING_V2`: Set this to `"true"` to enable LangChain tracing.

2. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

3. Enter your query in the text input field and click "Search" to receive a response from the LangChain BOT.

## Prompt Template

The prompt template defines the structure of the conversation between the user and the LangChain BOT. You can customize the prompt template in the `prompt` variable in the `app.py` file.

## Components

- **LangChain Core**: Provides the foundational components for working with LangChain's language processing capabilities.
- **LangChain Community**: Offers additional functionalities and integrations for specific use cases.
- **OLLAMA **: A language model adapter used to interface with LangChain's language models.


