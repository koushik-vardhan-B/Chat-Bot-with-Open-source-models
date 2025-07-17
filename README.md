# Enhanced Q&A Chatbot With OpenSource Models

This project is a simple Q&A chatbot built with [Streamlit](https://streamlit.io/) and open-source LLMs using [LangChain](https://python.langchain.com/). It supports model selection, temperature, and max token adjustments, and uses environment variables for API key management.

## Features

- Chatbot interface with Streamlit
- Supports open-source LLMs (e.g., Llama3)
- Adjustable temperature and max tokens
- Environment variable management with `.env`
- LangSmith tracking enabled

## Setup

1. **Clone the repository:**
   ```sh
   git clone git@github.com:koushik-vardhan-B/Chat-Bot-with-Open-source-models.git
   cd Chat-Bot-with-Open-source-models
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the project root:
     ```
     LANGCHAIN_API_KEY="your_langchain_api_key"
     ```

4. **Run the app:**
   ```sh
   streamlit run app.py
   ```

## Files

- [`app.py`](app.py): Main Streamlit app.
- [`requirements.txt`](requirements.txt): Python dependencies.
- [`.env`](.env): Environment variables (not committed to GitHub for security).

## Usage

- Open the app in your browser.
- Select the model and adjust parameters in the sidebar.
- Enter your question and get a response from the selected LLM.

## License

MIT License
