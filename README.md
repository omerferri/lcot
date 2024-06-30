# Linguistic Chain-of-Thoughts (L-CoT): Analysis of Language Model Reasoning Abilities Across Languages

## Overview

This repository consists of our research and results regarding the L-CoT (Linguistic Chain-of-Thought) method we wrote a paper about.
Below is a brief explanation regarding the paper and the files in this repository.

## Abstract

Large language models (LLMs) are renowned
for their impressive capabilities across a variety
of tasks. However, these models often exhibit
significant performance degradation when applied to tasks in languages other than English,
particularly in languages that are highly underrepresented in the training set. In this article,
we analyze the reasons behind this performance
degradation, categorizing the challenges into
two main areas: the difficulty of correctly understanding the problem, and the difficulty of
performing a step-by-step inference process accurately (by using chain-of-thought reasoning).
We evaluate the impact of each problem and
show that each one of them leads to significant results degradation by its own. Additionally, we propose a prompting method called
"Linguistic Chain-of-Thoughts" (L-CoT) that
addresses both challenges simultaneously, resulting in a substantial improvement in model
performance even in highly underrepresented
languages, and without additional cost in terms
of tokens usage. Our method achieves state of
the results on MGSM and XCOPA datasets

## Explanation
### Notebooks
- **Analyze results**: The notebook we used to extract the graphs and figures in our paper.
- **Datasets_example**: Can be used to view an example for a question in each dataset.
- **create_prepromtps_mgsm**: Was used by us to create the preprompts we gave to the models during our research.
- **gpt3.5_example**: Can be used to see an example of how we used OpenAI's API to run the models.
- **gpt3_5_on_mgsm**: The notebook we used to create the results of each experiment, with the GPT3.5 model.
- **gpt4o_on_mgsm**: The notebook we used to create the results of each experiment, with the GPT4o model.

## Results Graph

![Alt text](Resources/MGSM%20Full%20Comparison%20Graph.png?raw=true "MGSM Results")


