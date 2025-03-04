# Research Agent
AI-powered research agent that fetches relevant search results, summarizes information, and generates well-structured responses.

## Project Description
This project is an AI-powered research agent that retrieves information from the web and generates structured answers using advanced NLP models. It integrates **TavilySearchResults** for web search and **Hugging Face Inference API** for text generation. The system follows a two-step workflow:
1. **Research Agent**: Fetches relevant information on a given topic from the web.
2. **Answer Drafter Agent**: Processes the retrieved data and generates a structured answer.

## Features
- Web search capabilities using **TavilySearchResults**
- Text generation using **Hugging Face Inference API**
- Automated summarization of research topics
- Structured answer generation
- Modular and scalable design using **LangChain** and **LangGraph**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hillhack/Research-ai-agent
   cd research_agent
   ```
2. Create a virtual environment:
   ```bash
   python3 -m venv research_agent_env
   source research_agent_env/bin/activate  # On Windows use: research_agent_env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r installed_packages.txt
   ```
4. Set up environment variables:
   - Create a `.env` file and add:
     ```env
     TAVILY_API_KEY=your_tavily_api_key
     HUGGING_API_KEY=your_hugging_face_api_key
     ```

## Dependencies
- `langchain`
- `langgraph`
- `huggingface_hub`
- `tavily-python`
- `dotenv`



