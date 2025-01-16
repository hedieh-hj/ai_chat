# AI Chat

This project implements an AI-powered chat application using OpenAI's API, enabling interactive conversations and AI-driven tasks. The server is built using **FastAPI** and includes JWT authentication for secure access. It integrates multiple libraries such as **Langchain**, **PyJWT**, and **Pydantic** to enhance functionality and performance.


## Libraries Used

- **Unstructured**: For working with unstructured data like PDFs.
- **Langchain**: For language model integration.
- **OpenAI**: For accessing OpenAI's models.
- **PyJWT**: For managing JSON Web Tokens.
- **SQLAlchemy**: For database interactions.
- **Pydantic**: For data validation and model handling.

## Setup and Installation

Follow the steps to install dependencies and run the server.
```bash
pip install "unstructured[pdf]"
pip install langchain
pip install openai
pip install pyodbc
pip install pyjwt sqlalchemy passlib email-validator
pip install "python-jose[cryptography]" "passlib[bcrypt]" python-multipart
pip install pydantic
```

## run server
uvicorn python_file_name:app --reload

## source
https://testdriven.io/blog/fastapi-jwt-auth/ \
<br />
