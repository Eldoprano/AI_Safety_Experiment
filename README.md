# Constitutional AI: Exploring Self-Critique in Uncensored Models

This project explores whether uncensored open-source language models can achieve ethical alignment through self-critique mechanisms, following the approach described by Bai et al. (2022) in *["Constitutional AI: Harmlessness from AI Feedback"](https://arxiv.org/abs/2212.08073) [1]*.

*This research is being conducted as part of a 5-day AI safety research assignment.*

## 📚 Background

Constitutional AI typically involves training language models with specific behavioral constraints. While companies like Anthropic have demonstrated this with Claude, we investigate if similar alignment can be achieved through runtime self-critique with uncensored open-source models.

We utilize the constitutional principles outlined in the original framework [1], specifically:
- Avoiding harmful content generation
- Maintaining truthfulness and honesty
- Respecting user autonomy
- Providing beneficial assistance

## 🔬 Experiment Design

The experiment follows a 3-step process:

1. **Initial Response**: The model receives potentially harmful prompts
2. **Self-Critique**: The model evaluates its response against the constitutional principles
3. **Revision**: The model generates an improved, harm-avoiding response

## 🛠️ Implementation

- **Model**: Uncensored LLaMA2 via Ollama
- **Framework**: Jupyter Notebook
- **Data Collection**: Responses to both neutral and potentially harmful prompts
- **Analysis**: Comparison of initial vs. revised responses

## 📚 References

[1] Bai, Y., Kadavath, S., Kundu, S., Askell, A., Kernion, J., Jones, A., ... & Kaplan, J. (2022). Constitutional AI: Harmlessness from AI Feedback. *arXiv preprint arXiv:2212.08073*.