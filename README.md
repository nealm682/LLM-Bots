# LLM-Bots

# GitHub Repository Contents

## 1. [Chatbot](https://github.com/nealm682/LLM-Bots/blob/main/Chatbot.py)

This is a Streamlit application integrating OpenAI's gpt-3.5-turbo model to provide a conversational interface.

**Key Features**:
- Sidebar input for OpenAI API key.
- Interactive chat interface for querying the OpenAI model.
- Storage and display of ongoing conversation history.

```python
import openai
import streamlit as st
#... [remainder of the code]
```

## 2. [File Q&A](https://github.com/nealm682/LLM-Bots/blob/main/pages/1_File_Q%26A.py)

This application leverages the power of Anthropic's AI to answer questions based on uploaded text files.

**Key Features**:
- File uploader for `.txt` and `.md` files.
- Input for asking questions related to the uploaded file.

```python
import streamlit as st
import anthropic
#... [remainder of the code]
```

## 3. [Langchain prompt template](https://github.com/nealm682/LLM-Bots/blob/main/pages/4_Langchain_PromptTemplate.py)

A Streamlit app to generate blog outlines using the Langchain API integrated with OpenAI.

**Key Features**:
- Sidebar input for OpenAI API key.
- Form input to specify the topic for the blog outline.

```python
import streamlit as st
from langchain.llms import OpenAI
from langchain.prompts import PromptTemplate
#... [remainder of the code]
```

## 4. [Chat with user feedback](https://github.com/nealm682/LLM-Bots/blob/main/pages/5_Chat_with_user_feedback.py)

Incorporates user feedback on LLM responses, alongside the Trubrics backend for feedback logging.

**Key Features**:
- Inclusion of `streamlit-feedback` for collecting feedback.
- Chat interface with user feedback capabilities.

```python
import openai
import streamlit as st
from streamlit_feedback import streamlit_feedback
import trubrics
#... [remainder of the code]
```

## 5. [Chat with search](https://github.com/nealm682/LLM-Bots/blob/main/pages/2_Chat_with_search.py)

A chatbot with web search capabilities leveraging the Langchain API and DuckDuckGo.

**Key Features**:
- Can perform web searches to answer user queries.
- Sidebar for OpenAI API key input.

```python
import streamlit as st
from langchain.agents import initialize_agent, AgentType
#... [remainder of the code]
```

## 6. [Langchain quickstart](https://github.com/nealm682/LLM-Bots/blob/main/pages/3_Langchain_Quickstart.py)

Quick start application for the Langchain API integrated with OpenAI.

**Key Features**:
- Sidebar input for OpenAI API key.
- TextArea for user input and AI-generated responses.

```python
import streamlit as st
from langchain.llms import OpenAI
#... [remainder of the code]
```

---

Note: The provided links in the above markdown are placeholders, you should replace them with the actual links to your GitHub repository.