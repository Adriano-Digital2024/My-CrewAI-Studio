# AI Rules for CrewAI Studio

## Tech Stack

- **Framework**: The application is built using Streamlit, a Python library for creating web applications with minimal code.
- **Database**: The app uses SQLite for local data storage and PostgreSQL for production environments.
- **ORM**: SQLAlchemy is used as the ORM (Object-Relational Mapping) tool to interact with the database.
- **LLM Integration**: The app integrates with various LLM providers including OpenAI, Groq, Anthropic, Ollama, and LM Studio.
- **Web Scraping**: The app uses Scrapfly for advanced web scraping capabilities.
- **Search Tools**: DuckDuckGo search tool is integrated for web searches.
- **Code Execution**: The app uses Docker containers to execute Python code in a sandboxed environment.
- **File Handling**: The app supports various file formats including CSV, PDF, DOCX, JSON, and more.
- **Knowledge Sources**: The app supports different types of knowledge sources including text files, PDFs, CSVs, Excel files, and JSON files.

## Rules for Library Usage

1. **Streamlit**: Use Streamlit for all UI components and interactions. It is the primary framework for building the web interface.
2. **SQLite/PostgreSQL**: Use SQLite for local development and PostgreSQL for production environments. SQLAlchemy should be used as the ORM for database interactions.
3. **LLM Providers**: Use the provided LLM integration tools for interacting with different LLM providers. Ensure that the appropriate API keys are set in the environment variables.
4. **Scrapfly**: Use Scrapfly for advanced web scraping capabilities. Ensure that the Scrapfly API key is set in the environment variables.
5. **DuckDuckGo Search Tool**: Use the DuckDuckGo search tool for web searches. This tool is integrated into the app for searching the web.
6. **Code Execution**: Use Docker containers for executing Python code in a sandboxed environment. Ensure that Docker is installed and running on the system.
7. **File Handling**: Use the provided file handling tools for reading and writing different file formats. Ensure that the appropriate file paths are provided.
8. **Knowledge Sources**: Use the provided knowledge source tools for integrating different types of knowledge sources into the app. Ensure that the appropriate file paths or URLs are provided.

## Additional Guidelines

- **Environment Variables**: Ensure that all necessary environment variables are set before running the application. This includes API keys for LLM providers, Scrapfly, and other services.
- **Error Handling**: Implement proper error handling for all API calls and database interactions. Use try-catch blocks to handle exceptions and provide meaningful error messages.
- **Code Quality**: Follow Python coding standards and best practices. Use type hints and docstrings for better code readability and maintainability.
- **Testing**: Write unit tests and integration tests for all components. Ensure that the tests cover all critical paths and edge cases.
- **Documentation**: Maintain up-to-date documentation for the app. Include installation instructions, usage guidelines, and API documentation.

By following these rules and guidelines, you can ensure that the CrewAI Studio application is built and maintained in a consistent and efficient manner.