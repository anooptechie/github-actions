# GitHub Actions Demo

A simple Python project demonstrating GitHub Actions CI/CD workflows.

## Project Structure

```
.
├── src/
│   └── addition.py    # Simple addition function with tests
└── README.md
```

## Features

- Basic addition function implementation
- Unit tests using assertions

## Usage

```python
from src.addition import add

result = add(1, 2)  # Returns 3
```

## Running Tests

```bash
python -m pytest src/addition.py
```

Or run the test function directly:

```bash
python -c "from src.addition import test_add; test_add(); print('All tests passed!')"
```
