# UV-Based Python Project

A skeleton project using UV as the Python package manager.

## Setup

1. Install UV if you haven't already:

```bash
pip install uv
```

2. Create and activate a virtual environment:

```bash
uv venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:

```bash
uv pip install -r requirements.txt
```

4. Install the project in development mode:

```bash
uv pip install -e .
```

## Development

- Run the main module:

```bash
python -m my_uv_project.main
```

## Project Structure

- `src/my_uv_project/`: Source code directory
- `pyproject.toml`: Project configuration
- `requirements.txt`: Project dependencies
