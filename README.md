# End-To-End-Search-Engine-GEN-AI-App-using-Tools-And-Agent-With-Open-Source-LLM

### Overview
This project is an interactive chatbot application powered by LangChain and Streamlit that integrates advanced search capabilities using tools like Arxiv, Wikipedia, and DuckDuckGo. The chatbot provides real-time responses by leveraging large language models (LLMs) and search APIs to deliver accurate and relevant answers to user queries.

### Features
- **Interactive Chat Interface:** A user-friendly interface built with Streamlit for seamless interactions.
- **Search Tools Integration:** Includes tools for fetching content from:
- **Arxiv:** Academic papers and research articles.
- **Wikipedia:** Summarized content from the largest online encyclopedia.
- **DuckDuckGo:** Web search results for general queries.
- **LLM Integration:** Uses the ChatGroq model for natural language understanding and generating contextual responses.
- **Session Management:** Maintains chat history during user sessions for a conversational experience.
- **Callback Monitoring:** Displays the agent's thought process and actions using the StreamlitCallbackHandler.
### How It Works
- **Setup API Key:**

Users input their Groq API key in the Streamlit sidebar to authenticate the LLM.
- **Chat Interface:**

Users interact with the chatbot by typing questions or prompts into the chat input box.
Previous conversations are displayed for context.
- **Search and Response Generation:**

The chatbot leverages the integrated tools (Arxiv, Wikipedia, DuckDuckGo) to fetch relevant information.
The ChatGroq LLM processes the user's query and combines it with the retrieved data to generate a response.
- **Streaming Output:**

Responses are streamed in real-time, giving users immediate feedback.
- **Error Handling:**

Utilizes LangChain's error handling features to gracefully manage parsing errors and incomplete responses.

### Prerequisites
- **Python 3.9 or later**
- **Required Python packages:**
- **streamlit**
- **langchain**
- **langchain_groq**
- **langchain_community**
- **python-dotenv**

