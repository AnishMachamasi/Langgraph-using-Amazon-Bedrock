# LangChain Academy

## Introduction

Welcome to LangChain Academy!
This is a growing set of modules focused on foundational concepts within the LangChain ecosystem.
Module 0 is basic setup and Modules 1 - 4 focus on LangGraph, progressively adding more advanced themes.
In each module folder, you'll see a set of notebooks. A LangChain Academy accompanies each notebook
to guide you through the topic. Each module also has a `studio` subdirectory, with a set of relevant
graphs that we will explore using the LangGraph API and Studio.

## Setup

### Python version

To get the most out of this course, please ensure you're using Python 3.11 or later.
This version is required for optimal compatibility with LangGraph. If you're on an older version,
upgrading will ensure everything runs smoothly.

```
python3 --version
```

### Clone repo

```
git clone https://github.com/langchain-ai/langchain-academy.git
$ cd langchain-academy
```

### Create an environment and install dependencies

#### Mac/Linux/WSL

```
$ python3 -m venv lc-academy-env
$ source lc-academy-env/bin/activate
$ pip install -r requirements.txt
```

#### Windows Powershell

```
PS> python3 -m venv lc-academy-env
PS> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
PS> lc-academy-env\scripts\activate
PS> pip install -r requirements.txt
```

### Running notebooks

If you don't have Jupyter set up, follow installation instructions [here](https://jupyter.org/install).

```
$ jupyter notebook
```

### Sign up and Set LangSmith API

- Sign up for LangSmith [here](https://smith.langchain.com/), find out more about LangSmith
- and how to use it within your workflow [here](https://www.langchain.com/langsmith), and relevant library [docs](https://docs.smith.langchain.com/)!
- Set `LANGCHAIN_API_KEY`, `LANGCHAIN_TRACING_V2=true` in your environment

### Set up Tavily API for web search

- Tavily Search API is a search engine optimized for LLMs and RAG, aimed at efficient,
  quick, and persistent search results.
- You can sign up for an API key [here](https://tavily.com/).
  It's easy to sign up and offers a very generous free tier. Some lessons (in Module 4) will use Tavily.

- Set `TAVILY_API_KEY` in your environment.
