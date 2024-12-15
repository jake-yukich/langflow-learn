Dev Log

2024-12-04
- 
Installed `uv`.

Setup a virtual environment as follows:
```bash
uv venv --python 3.12

# Using CPython 3.12.7 interpreter at: /opt/homebrew/opt/python@3.12/bin/python3.12
# Creating virtual environment at: .venv
# Activate with: source .venv/bin/activate
# Deactivate with: deactivate
```

Installed `Langflow`:
```bash
source .venv/bin/activate
uv pip install langflow
```

Run `Langflow` UI:
```bash
uv run langflow run
# visit http://127.0.0.1:7860/ in a Chromium-based browser
```
2024-12-05
- 
`uv run langflow run` → New Flow → Basic Prompting

 [x] get an OpenAI API key


