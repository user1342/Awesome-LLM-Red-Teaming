# Awesome LLM Red Teaming

<p align="center">
   <img width=100% src="LLM.gif">
</p>

<p align="center">
A comprehensive list of tools and resources for red-teaming large language models (LLMs), vulnerability research, and reverse engineering using various techniques like prompt manipulation, adversarial testing, and model interpretation.
</p>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://github.com/user1342/Awesome-LLM-Red-Teaming)
![GitHub contributors](https://img.shields.io/github/contributors/user1342/Awesome-LLM-Red-Teaming)
![GitHub Repo stars](https://img.shields.io/github/stars/user1342/Awesome-LLM-Red-Teaming?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/user1342/Awesome-LLM-Red-Teaming?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/user1342/Awesome-LLM-Red-Teaming)
<br>

</div>

# How to Use

Awesome LLM Red Teaming is a curated list for researchers, engineers, and enthusiasts focused on exploring, testing, and securing large language models. Use `ctrl + F` to search for keywords, explore our Contents menu, or look for a '☆' symbol for standout resources.

# Contents

- [Tools](#tools)
  - [Reverse Engineering and Analysis](#reverse-engineering-and-analysis)
  - [Prompt Manipulation and Control](#prompt-manipulation-and-control)
  - [Adversarial Attack and Defense](#adversarial-attack-and-defense)
  - [Bias and Toxicity Detection](#bias-and-toxicity-detection)
  - [Miscellaneous](#miscellaneous)
- [Techniques and Approaches](#techniques-and-approaches)
- [Research Papers](#research-papers)
- [Tutorials and Guides](#tutorials-and-guides)
- [Communities and Forums](#communities-and-forums)
- [Contributing](#contributing)
- [License](#license)

---

# Tools

## Reverse Engineering and Analysis

- **[☆ Oversight](https://github.com/user1342/Oversight)** - A modular framework for reverse engineering, red-teaming, and vulnerability research in LLMs. 
- **[TextAttack](https://github.com/QData/TextAttack)** - Framework for adversarial text generation and NLP vulnerability testing, with support for adversarial attack creation, data augmentation, and model defense.

## Prompt Manipulation and Control

- **[☆ Abliteration](https://huggingface.co/blog/mlabonne/abliteration)** - Tool for bypassing content filters in LLMs, revealing the model’s full generation capabilities.
- **[CTRL by Salesforce](https://github.com/salesforce/ctrl)** - A conditional transformer model that enables prompt-based control, helping researchers analyze how prompts affect LLM behavior.
  
## Adversarial Attack and Defense

- **[TextFooler](https://github.com/jind11/TextFooler)** - An adversarial attack tool that generates subtle input perturbations to deceive NLP models, applicable for robustness testing in LLMs.
- **[Perspective API](https://perspectiveapi.com/)** - Tool for measuring and filtering toxicity in LLM outputs, widely used to assess bias and harmful output in language models.

## Bias and Toxicity Detection

- **[Hugging Face's Model Cards and Datasets](https://huggingface.co/models)** - Collection of LLMs with transparency on biases, limitations, and safety warnings. Model cards are essential for red-teaming bias in model deployment.
- **[Toxicity Detection with Detoxify](https://github.com/unitaryai/detoxify)** - Model to classify toxic language and analyze bias in LLM outputs, essential for robustness and ethics in NLP.
- **[RealToxicityPrompts](https://github.com/allenai/real-toxicity-prompts)** - Dataset designed to evaluate and address model responses that might lead to toxic or harmful outputs.

## Miscellaneous

- **[Prompt Engineering Tools](https://www.promptengineering.org)** - A resource for learning about prompt engineering, which includes various prompt manipulation techniques useful for red-teaming.
  
# Techniques and Approaches

- **Prompt Injection and Manipulation** - Using prompt engineering techniques to manipulate and probe LLM behavior by injecting unexpected commands or context.
- **Adversarial Attack Generation** - Creating adversarial examples to test the model's susceptibility to perturbations, such as synonym replacements, input rearrangement, and semantic changes.
- **Hallucination Testing** - Evaluating model consistency and accuracy by prompting for factual information, then checking for potential model hallucinations.
- **Uncensoring and Content Filter Bypass** - Techniques for disabling content filters to study hidden model behaviors and raw generative capabilities.
- **Bias and Toxicity Detection** - Tools and metrics for assessing LLM outputs for bias and toxicity to ensure responsible and ethical deployment.

# Research Papers

- **[TruthfulQA: Measuring How Models Mimic Human Falsehoods](https://arxiv.org/abs/2109.07958)** - Benchmark paper on the truthfulness of model outputs, addressing hallucination in LLMs.
- **[Understanding and Mitigating Hallucinations in LLMs](https://ieeexplore.ieee.org/abstract/document/10569238/)** - Examines how hallucinations emerge in LLMs and suggests approaches for detecting and addressing this issue.

# Tutorials and Guides

- **[☆ Hugging Face's Guide to Red-Teaming LLMs](https://huggingface.co/blog/red-teaming)** - Covers best practices for ethically red-teaming LLMs, with examples on probing biases and adversarial testing.
- **[Planning red teaming for large language models (LLMs) and their applications](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming)** - This guide offers some potential strategies for planning how to set up and manage red teaming for responsible AI (RAI) risks throughout the large language model (LLM) product life cycle.
- **[Using TextAttack for Adversarial Example Generation](https://textattack.readthedocs.io/en/latest/)** - Tutorial on creating adversarial text samples with TextAttack to probe weaknesses in LLMs.
- **[Prompt Engineering for Red Teaming](https://promptengineering.org)** - Techniques for prompt injection and manipulation, useful for understanding LLM vulnerabilities and testing prompt-responsiveness.

# Communities and Forums

- **[Hugging Face Community](https://discuss.huggingface.co/)** - Platform for discussing LLM development, testing, and ethical considerations with a strong focus on responsible AI practices.
- **[EleutherAI Discord](https://www.eleuther.ai/)** - Open-source AI research community with discussions on language model security, vulnerabilities, and adversarial testing.
- **[r/MachineLearning](https://www.reddit.com/r/MachineLearning/)** - Popular Reddit forum for discussions on LLM research, vulnerability testing, and model robustness.
- **[OpenAI's Red Teaming Network](https://openai.com/form/red-teaming-network/)** - OpenAI’s network for red-teaming and vulnerability analysis for language models.

# Contributing

Your contributions are always welcome! Please read the contribution guidelines first. We follow the Contributor Covenant Code of Conduct. Please make sure to review and adhere to this code of conduct when contributing.

# License <a href="LICENSE">![GitHub](https://img.shields.io/github/license/user1342/Awesome-LLM-Red-Teaming)</a>

This project is licensed under the MIT License - see the LICENSE.md file for details.
