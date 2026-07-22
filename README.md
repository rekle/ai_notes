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

### 1 bit vs Ternary (1.58 bit) Models

1 bit models run faster with a lot less memory usage because they only use 1 bit of memory for each weight.  The two values you can store in 1 bit indicate that the weight is either more relevant or less relevant.  

Ternary (aka 1.58 bit models), adds a 'not relevant' state, so 3 states are now possible for each weight and it needs 2 bits to store each weight.  This leads to more cmplex math, slower operation, and a lot more memory used.  The '1.58 bit' refers to the fact that you need 1.58 bits to store 3 possible values, though you can't really store a '0.58 bit', so it's really 2 bits.

Confusingly, some places refer to 1.58 bit models as 1 bit models.

### Parameters

Data points used to calculate an AI's response.  Higher numbers mean more complex models.

## Tools / Resources

### [Google AI Studio](https://aistudio.google.com/welcome)

### [Hugging Face](https://huggingface.co)

### [Ollama](https://ollama.com)

### [OpenClaw](https://openclaw.ai)

Personal AI Assistant

### [Osaurus](https://osaurus.ai)

Run downloadable models locally on a Mac without any subscriptions, network use etc.

### [Tiny Weights](https://tinyweights.dev)

Blog about testing Small Language Models.

### Google AI Studio

## Glossary

* AI - Artificial Intelligence
* LLM - Large Language Model
* MCP - [Model Context Protocol](https://modelcontextprotocol.io/docs/getting-started/intro) - Provides a common way of an AI accessing data from a particular data source.
* ML - Machine Learning
* SLM(?) - Small Language Models - Models designed to run in constrained environments (low RAM/CPU), such as mobile devices.

