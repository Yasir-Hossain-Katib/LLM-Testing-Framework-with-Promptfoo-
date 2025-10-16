# promptfoo_test

This repository contains configuration files to run promptfoo tests for comparing LLM responses. It appears to be a minimal project used for evaluating or comparing OpenAI/Ollama-style LLM prompts.

## Contents

- `promptconfig.yaml` - Prompt configuration (input prompts, variables, or scenarios).
- `promptfooconfig.yaml` - promptfoo configuration used to define how prompts are run, the model, and evaluation settings.

> Note: The repository currently only contains configuration files. There is no test harness or scripts included.

## Purpose

This project stores prompt definitions and test configuration for running promptfoo-based evaluations of LLMs. Use it to keep repeatable prompt tests, share prompts, and compare outputs across models or model versions.

## How to use

1. Install `promptfoo` (or your preferred prompt testing tool) per its docs. For example, with npm:

```bash
npm install -g @promptfoo/promptfoo-cli
```

2. Inspect and edit the YAML files to add or change prompts and test parameters.

3. Run your prompt tests using the promptfoo CLI or your test harness. Example (adjust to your CLI):

```bash
promptfoo run --config promptfooconfig.yaml
```

4. Review outputs and evaluation results.

## Files

- `promptconfig.yaml`: Example prompts and variables. Edit before running.
- `promptfooconfig.yaml`: Controls which prompts to run, model settings, and run options.

## Next steps / Suggestions

- Add a simple runner script (Node.js or Python) that invokes promptfoo with the correct config.
- Add example prompt results and expected outputs for automated assertions.
- Add a CONTRIBUTING.md and LICENSE.

## License

Add a license file to clarify usage (MIT suggested).
