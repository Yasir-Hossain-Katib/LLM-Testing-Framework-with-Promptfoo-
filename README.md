# LLM Testing Framework using Promptfoo

A hands-on project to **evaluate and compare multiple Large Language Models (LLMs)** using [Promptfoo](https://promptfoo.dev/).  
This project benchmarks two **local AI models – Gemma 2B and Mistral 7B** – by testing them with structured prompts and analyzing their outputs side by side.

---

## Project Overview

The goal of this project is to understand how different **AI models** respond to the same prompts and measure differences in:
- Explanation clarity  
- Factual accuracy  
- Contextual reasoning  
- Simplicity and tone

All tests are performed **locally** using [Ollama](https://ollama.ai/), ensuring privacy and full control over the evaluation process.

---

## Tools & Technologies

 - **Promptfoo** | Framework for LLM testing and comparison |
 - **Ollama** | Run LLMs locally (offline) |
 - **Gemma 2B (Google)** | Local model for reasoning and text generation |
 - **Mistral 7B (Mistral AI)** | Local model with advanced reasoning ability |
 - **YAML Configuration** | Defines prompts, models, and tests |

---
## How to Run the Evaluation

Install Ollama:
 - Download from Ollama.ai and run the models

In local terminal:
```
ollama pull gemma:2b
ollama pull mistral:7b-instruct
```

Install Promptfoo:
```
npm install -g promptfoo
```

Run the Evaluation
```
promptfoo eval -c promptfooconfig.yaml
```

View Results in Web UI
```
promptfoo view
```

2025-10-16 18-16-29.mkv
Add files via upload
now

## Both Models have different outputs when they are asked to explain LLM
![./assets/Screenshot%20from%202025-10-16%2018-20-49.png]


## Promptfoo Generated Automated Prompt Evaluation
![Promptfoo Result](./assets/2025-10-16%18-16-29.mkv)





