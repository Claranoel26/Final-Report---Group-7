# Final Report - Group 7

# Revisiting Skill Extraction in the Job Market Domain using Large Language Models

This repository contains the code and results for a reproduction study of the SCESC benchmark for skill extraction using large language models.

## Project Description
This project is based on the methodology introduced in the paper:
"Rethinking Skill Extraction in the Job Market Domain using Large Language Models" (Zhang et al., 2023).

We use the official SCESC implementation to reproduce selected experiments on the GREEN dataset, focusing on few-shot skill extraction with Extract and NER prompting strategies.

## Original Repository
The original implementation is available at:
https://github.com/epfl-nlp/SCESC-LLM-skill-extraction

## Experiments Reproduced
- Dataset: GREEN
- Prompting strategies: Extract, NER
- Models: GPT-3.5-Turbo, GPT-4o-mini, GPT-4o (5-shot only)
- Number of shots: 1, 5, 10, 20

The experimental results are stored in the `results/` directory.

## Reproducibility
To reproduce the experiments:
1. Clone this repository.
2. Install the required dependencies (see original repository).
3. Set your OpenAI API key.
4. Run the experiment scripts following the instructions from the original SCESC repository.

Due to API costs and time constraints, only a subset of the experiments from the original paper were reproduced.

## Authors
Lucie Bartosova  
Clara Guillemet  
Clara Noel
