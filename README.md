# Translation Service

This project implements a robust and scalable translation service using FastAPI, SQLAlchemy, and PostgreSQL. It allows users to submit text for translation into multiple languages, track the status of their translation requests, and retrieve the translated results.

## Features

*   **Asynchronous Translation**: Handles translation requests in the background to ensure a responsive user experience.
*   **Multiple Language Support**: Translate text into various target languages.
*   **Request Tracking**: Monitor the status of translation requests (e.g., "in progress", "completed").
*   **Database Integration**: Persists translation requests and results using SQLAlchemy with a PostgreSQL database.
*   **Web Interface**: Simple HTML templates for submitting translation requests and viewing results.
*   **CORS Enabled**: Configured to allow cross-origin requests.

## Technologies Used

*   **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints.
*   **Uvicorn**: An ASGI server for running FastAPI applications.
*   **SQLAlchemy**: The Python SQL Toolkit and Object Relational Mapper, used for database interactions.
*   **PostgreSQL**: A powerful, open-source relational database system.
*   **Asyncpg**: A PostgreSQL driver for Python, designed for use with the `asyncio` framework.
*   **Psycopg2-binary**: A PostgreSQL adapter for Python.
*   **Jinja2**: A modern and designer-friendly templating language for Python.
*   **OpenAI**: Used for the actual translation process (assuming `openai` library is used for an external translation API).

