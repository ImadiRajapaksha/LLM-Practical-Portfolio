# LLM Practical Portfolio

A hands-on portfolio of six practical labs on Large Language Models and Generative AI, built progressively from classical NLP to tool-using AI agents.

## Labs

| # | Lab | Focus | Status |
|---|-----|-------|--------|
| 01 | [Machine Learning](Lab-01-Machine-Learning/) | Sentiment analysis with text preprocessing, Bag-of-Words and classical ML | Complete |
| 02 | [LLMs in Everyday Life](Lab-02-LLM-Everyday-Life/) | Designing a student product with an LLM as a development partner | Pending |
| 03 | [Tiny Transformer](Lab-03-Tiny-Transformer/) | A small GPT-style language model trained on TinyStories | Pending |
| 04 | [Fine-Tuning](Lab-04-Fine-Tune/) | LoRA/QLoRA fine-tuning of a small instruction-tuned LLM | Pending |
| 05 | [RAG Pipeline](Lab-05-RAG-Pipeline/) | Retrieval-Augmented Generation with LangChain, ChromaDB, Ollama and Streamlit | Pending |
| 06 | [AI Agents](Lab-06-AI-Agents/) | Tool-using agents with memory, RAG and n8n workflow automation | Pending |

See [Final-Reflection.md](Final-Reflection.md) for a summary of what was learned across the labs.

## Tech Stack

Python 3.12, Jupyter, scikit-learn, NLTK, PyTorch, Hugging Face Transformers, PEFT, TRL, LangChain, ChromaDB, Ollama, Streamlit, SQLite, n8n, Docker.

## Repository Structure

Each lab folder contains its own `README.md` with the objective, implementation, results, observations and learning outcomes, plus the notebooks and screenshots that support it.

## Setup

Each lab lists its own requirements in its folder. Create a virtual environment per lab:

```bash
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Author

Imadi Rajapaksha