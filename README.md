# 🔍 GitHub Repo Analyzer with SambaNova

Analyze and refactor GitHub code using LLMs powered by SambaNova’s blazing-fast RDU chips and Llama 4 Maverick.

## 🚀 Features
- Ingest any public GitHub repo with `gitingest`
- Use LLM to explain Python files (e.g., `model.py`)
- Get code refactor suggestions via natural language
- OpenAI-compatible, runs in notebooks or scripts

## 🛠️ Setup

```bash
pip install -U gitingest openai nest-asyncio
Update your API key:

✅ Example
We analyzed snake-ai-pytorch and asked:

"What does model.py do?"

"Refactor the save() function using pathlib"

LLM instantly returned human-readable insights and cleaner code! 🧠⚡

