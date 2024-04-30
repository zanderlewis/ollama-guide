# Ollama-Python Guide
A begginer-friendly guide to Ollama-Python.

Please note that this repo does not contain a guide to all the models supported by Ollama.

Please note that this repo is a work in progress. Contributions are welcome.

## What is Ollama?
Ollama is an application for running LLMs and Multi-Modals easily on a device. Ollama uses a REST API on a localhost to interact with different AI.

## What is Ollama-Python?
Ollama-Python is the official python library for interacting with LLMs and Multi-Modals.

## Requirements
In order to start using the Ollama-Python library, you must have [Ollama](https://ollama.com) installed on your device.

- Download [Ollama](https://ollama.com)
- Install the python library via `pip install ollama`
- You are all set! (Make sure Ollama is running before you continue)

## Models
Some models you can run via Ollama:

| Model              | Parameters | Size  | Download                       |
| ------------------ | ---------- | ----- | ------------------------------ |
| Llama 3            | 8B         | 4.7GB | `ollama run llama3`            |
| Llama 3            | 70B        | 40GB  | `ollama run llama3:70b`        |
| Phi-3              | 3,8B       | 2.3GB | `ollama run phi3`              |
| Mistral            | 7B         | 4.1GB | `ollama run mistral`           |
| Neural Chat        | 7B         | 4.1GB | `ollama run neural-chat`       |
| Starling           | 7B         | 4.1GB | `ollama run starling-lm`       |
| Code Llama         | 7B         | 3.8GB | `ollama run codellama`         |
| Llama 2 Uncensored | 7B         | 3.8GB | `ollama run llama2-uncensored` |
| LLaVA              | 7B         | 4.5GB | `ollama run llava`             |
| Gemma              | 2B         | 1.4GB | `ollama run gemma:2b`          |
| Gemma              | 7B         | 4.8GB | `ollama run gemma:7b`          |
| Solar              | 10.7B      | 6.1GB | `ollama run solar`             |

There are more models on their website. You can find the list [here.](https://ollama.com/library)

> Note: According to Ollama, you should have at least 8 GB of RAM available to run the 7B models, 16 GB to run the 13B models, and 32 GB to run the 33B models.

## Getting Started
Please visit [here](getting-started.md) to get started.
