# AIPI 590 - XAI - Mechanistic Interpretability

## Explaining a Parity Neuron [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ailina-aniwan/xai-mechanistic-interpretability/blob/main/mechanistic_interp.ipynb)

### Overview

This project investigates the internal behavior of a tiny neural network trained on a simple 5-bit parity classification task. The aim is to understand how the model forms internal representations—treating it like a small “tiny brain” whose components can be examined, tested, and explained. Using a lightweight multilayer perceptron (MLP), I analyze how individual hidden neurons respond to input patterns and what functions they appear to encode.

A key result from this exploration is the identification of an interpretable hidden unit: Neuron 6, which behaves like a low-weight, left-bit detector. It activates most strongly when one or two early bits are on and remains quiet for more complex patterns, suggesting a focused sub-feature the model uses to help distinguish odd from even parity.

### Project Contents

The accompanying Google Colab notebook walks through the complete workflow:

- training a custom parity-classification model
- visualizing weight matrices, hidden activations, and neuron selectivity
- identifying and analyzing a single interpretable neuron
- testing how that neuron responds to controlled input changes
- explaining its functional role within the model
- reflecting on the interpretability process

### How to Use

Click the Colab badge above to open and run the notebook interactively. All code cells, visualizations, and explanations are included directly in the notebook to provide a clear, narrative walkthrough of the interpretability analysis.

### AI Citation

AI tools (ChatGPT, GPT-5) were used to support parts of this assignment. Specific uses and citations are documented within the notebook cells.