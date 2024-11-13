# Self-Critique of an Uncensored Open Source Model Using Constitutional AI

This project explores whether uncensored open-source language models can achieve ethical alignment through self-critique mechanisms, similar to the approach described in Anthropic's [Constitutional AI paper](https://arxiv.org/abs/2212.08073). 
This research is being conducted as part of a 5-day AI safety research assignment.

## 📚 Background

Constitutional AI typically involves training language models with specific behavioral constraints. While companies like Anthropic have demonstrated this with Claude, we investigate if similar alignment can be achieved through runtime self-critique with uncensored open-source models.

## 🔬 Experiment Design

The experiment follows a 3-step process:

1. **Initial Response**: The model receives potentially harmful prompts
2. **Self-Critique**: The model evaluates its response against ethical principles
3. **Revision**: The model generates an improved, harm-avoiding response

## 🛠️ Implementation

- **Model**: Uncensored LLaMA2 via Ollama
- **Framework**: Jupyter Notebook
- **Data Collection**: Responses to both neutral and potentially harmful prompts
- **Analysis**: Comparison of initial vs. revised responses