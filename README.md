# Simple Python Server based on Langflow codebase.

## Instructions on using Poetry

To use Poetry for managing dependencies and virtual environments, follow these steps:

1. Install Poetry by running the following command in your terminal:
  ```bash
  curl -sSL https://install.python-poetry.org | python3 -
  ```

2. Navigate to your project directory and initialize Poetry by running:
  ```bash
  poetry init
  ```

3. Follow the prompts to provide information about your project.

4. Add dependencies to your project by running:
  ```bash
  poetry add package_name
  ```

5. Poetry will automatically create a virtual environment for your project and install the specified package.

6. To activate the virtual environment, run:
  ```bash
  poetry shell
  ```

7. You can now run your Python server using Poetry.
```bash
poetry run dev
```

# modules

## API
- [FastAPI](https://fastapi.tiangolo.com/) - for api routes
- [socket.io](https://socket.io/) - Bidirectional and low-latency communication

## Logging
- [loguru](https://github.com/Delgan/loguru)

## Task Queue
- [Celery](https://docs.celeryproject.org/en/stable/getting-started/introduction.html)

## Data validation - typing
- [pydantic](https://docs.pydantic.dev/latest/)
- [pydantic-settings](https://docs.pydantic.dev/latest/concepts/pydantic_settings/) - provides optional Pydantic features for loading a settings or config class from environment variables or secrets files.
- [typer](https://pypi.org/project/typer/) - Typer, build great CLIs. Easy to code. Based on Python type hints.

## Multicore - Process-based parallelism
- [multiprocessing](https://docs.python.org/3/library/multiprocessing.html)

## HTTP
- [Gunicorn](https://gunicorn.org/) WSGI HTTP Server for unix

## Testing 
- [pytest](https://docs.pytest.org/en/6.2.x/)

## Linting
- [Ruff](https://github.com/astral-sh/ruff)

## AI
- [Langchain](https://python.langchain.com/v0.1/docs/get_started/introduction)



# Docs
- [docusarus](docusaurus) - refer to this https://github.com/langflow-ai/langflow/blob/dev/docs/package.json
- [sphinx](https://www.sphinx-doc.org/en/master/) - python documentation generator
<!-- - [readthedocs](https://readthedocs.org/) - hosting for sphinx documentation -->

```bash
cd docs
npx docusaurus start
```

Open http://localhost:3000 and follow the tutorial.

# Notes
Look into poetry groups for managing dependencies over multiple environments