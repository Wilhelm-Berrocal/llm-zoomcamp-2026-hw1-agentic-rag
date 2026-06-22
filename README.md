# LLM Zoomcamp 2026 - Module 1: Agentic RAG

This repository contains my homework workspace for Module 1 of LLM Zoomcamp 2026. The goal is to build and compare Retrieval-Augmented Generation (RAG) approaches over the course lesson markdown files from GitHub.

## What This Homework Covers

- Loading course lesson markdown files from GitHub.
- Building a retrieval index with `minsearch`.
- Implementing full-document RAG.
- Implementing chunked RAG.
- Comparing prompt size and behavior between full-document and chunked RAG.
- Building the agentic RAG part with PydanticAI.

## Setup

This project uses `uv` for dependency management.

```bash
uv sync
```

## Environment Variables

Secrets should be stored in `.env` and must not be committed. Create your local environment file from the example:

```bash
cp .env.example .env
```

Then edit `.env` and replace the placeholder value:

```bash
OPENAI_API_KEY=your_key_here
```

The `.env` file is ignored by git.

## Launch Jupyter

After installing dependencies, start Jupyter with:

```bash
uv run jupyter notebook
```

Open the homework notebook from the Jupyter interface.

## Expected Files

- `README.md` - project overview and setup instructions.
- `pyproject.toml` - project metadata and dependencies.
- `uv.lock` - locked dependency versions.
- `.env.example` - example environment variable template.
- `homework.ipynb` - Jupyter notebook solution for the homework.

Local-only files:

- `.env` - local secrets file, ignored by git and not committed.
