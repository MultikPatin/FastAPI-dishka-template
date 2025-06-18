# FastAPI Dishka Template

## Pre commit hooks

To install tool, run the following command:

```bash
uv tool install pre-commit
```

To install the pre-commit hooks, run the following command:

```bash
pre-commit install
```

To manual run all the pre-commit hooks, run the following command:

```bash
pre-commit run --all-files
```

## Running the application

To run the application, run the following command:

```bash
uvicorn src/composites/main:app --reload
```