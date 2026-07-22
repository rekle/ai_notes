# AI Notes

This repo contains my notes regarding AI.

## Open Models

### Bonsai 27b

Vendor: [PrismXL](https://prismml.com)

### Gemma 4 12B

Vendor: [Google Deepmind](https://deepmind.google)

### Gemma 4 E4B

Vendor: [Google Deepmind](https://deepmind.google)

### Gemma 4 E2B

Vendor: [Google Deepmind](https://deepmind.google)

### Ornith 1.0 9B

Vendor: [Ornith AI](https://ornith.online)

### Ornith 1.0 35B

Vendor: [Ornith AI](https://ornith.online)

## Paid Models

### Claude Code

Vendor: [Anthropic](https://www.anthropic.com)

Useful for: Writing Code

### Codex

Vendor: [OpenAI](https://openai.com)

Useful for: Writing Code

### OpenClaw

## Concepts

### 1-Bit vs Ternary

1-Bit models run faster with a lot less memory usage because they only use 1 bit of memory for each weight.  The two values you can store in 1 bit indicate that the weight is either more relevant or less relevant.  Ternary, adds a 'not relevant' state, so 3 states are now possible for each weight and it needs 2 bits to store each weight.  This leads to more cmplex math, slower operation, and a lot more memory used.

### Parameters

Data points used to calculate an AI's response.  Higher numbers mean more complex models.

## Tools / Resources

### [Osaurus](https://osaurus.ai)

Run downloadable models locally on a Mac without any subscriptions, network use etc.

### [Ollama](https://ollama.com)

### [Hugging Face](https://huggingface.co)

### [OpenClaw](https://openclaw.ai)

### [Tiny Weights](https://tinyweights.dev)

Blog about testing Small Language Models.

Personal AI Assistant

### Google AI Studio

## Glossary

* AI - Artificial Intelligence
* LLM - Large Language Model
* MCP - [Model Context Protocol](https://modelcontextprotocol.io/docs/getting-started/intro) - Provides a common way of an AI accessing data from a particular data source.
* ML - Machine Learning
* SLM(?) - Small Language Models - Models designed to run in constrained environments (low RAM/CPU), such as mobile devices.

