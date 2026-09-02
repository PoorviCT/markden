# Python Template Qatalyst

A minimal Python/FastAPI starter template.

## Prerequisites

- [Python 3.12+](https://www.python.org/downloads/)
- [uv](https://docs.astral.sh/uv/getting-started/installation/)

## Getting Started

```bash
# Install dependencies
uv sync

# Run the development server
uv run uvicorn app.main:app --reload

# Run tests
uv run pytest
```

The API will be available at [http://localhost:8000](http://localhost:8000).

## API Endpoints

| Method | Path      | Description          |
| ------ | --------- | -------------------- |
| GET    | `/`       | Hello World response |
| GET    | `/health` | Health check         |

## Project Structure

```text
.
├── app/
│   ├── __init__.py
│   └── main.py          # FastAPI application
├── tests/
│   └── test_main.py     # Tests
├── pyproject.toml        # Project configuration
├── uv.lock               # Locked dependencies
├── .gitignore
└── README.md
```
