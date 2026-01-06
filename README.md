# SQL Query Generator

A simple yet powerful tool that generates SQL queries from natural language using Groq's LLaMA 3 model. This project runs entirely on LLM logic and does not require an active database connection.

## Features

- 🗣️ **Natural Language to SQL**: Convert English questions into valid SQL queries.
- 📊 **Result Simulation**: Generates realistic sample data tables to preview query results.
- 🚀 **FastAPI Backend**: High-performance backend serving the API.
- 💻 **Simple UI**: Clean interface to interact with the generator.

## Prerequisites

- Python 3.8+
- [Groq API Key](https://console.groq.com/keys)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tejas4560/SQL_QueryGenerartor.git
   cd SQL_QueryGenerartor
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment:**
   Create a `.env` file in the root directory and add your Groq API key:
   ```env
   GROQ_API_KEY=your_api_key_here
   ```

## Usage

1. **Start the server:**
   ```bash
   uvicorn main:app --reload
   ```

2. **Access the application:**
   Open your browser and navigate to `http://localhost:8000`.

3. **Generate SQL:**
   - Type your question (e.g., "Show me all students who scored above 90").
   - Click "Generate".
   - View the generated SQL and sample results.

## Tech Stack

- **Backend**: FastAPI
- **AI/LLM**: LangChain, Groq (LLaMA 3)
- **Frontend**: HTML/JS (Static)

## License

This project is open source and available under the [MIT License](LICENSE).
