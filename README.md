# OpenAI Agents SDK – Quickstart

Practice project following the official
[OpenAI Agents SDK (Python) quickstart](https://openai.github.io/openai-agents-python/quickstart/).

Each tutorial section is saved as its own runnable script:

| File | Tutorial section |
| --- | --- |
| `01_hello_agent.py` | Create your first agent |
| `02_tools.py` | Give your agent tools |
| `03_multiple_agents.py` | Add a few more agents |

## Requirements

- Python 3.10 or later
- An OpenAI API key ([create one here](https://platform.openai.com/api-keys))

## Installation

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install openai-agents
```

## Usage

```bash
export OPENAI_API_KEY="sk-..."
python 01_hello_agent.py
```

## References

- Tutorial: https://openai.github.io/openai-agents-python/quickstart/
- SDK documentation: https://openai.github.io/openai-agents-python/
- SDK repository: https://github.com/openai/openai-agents-python
