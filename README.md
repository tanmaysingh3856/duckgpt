# DuckGPT

DuckGPT is a Python client for interacting with the DuckGPT.

## Installation

```bash
pip3 install duckgpt
```

## Usage

```python
from duckgpt import DuckGPT

client = DuckGPT(model="gpt-4o-mini")
models = client.Models()
response = client.Chat("Hello, world!", [])
print(response)
```

## Owner
[Tanmay Singh](https://github.com/tanmaysingh3856)