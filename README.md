# nanoGPT Arithmetic Tool-Use
 
## Project Overview
 
This project is the foundational architecture for an LLM-driven calculator agent, developed in Spring 2026. The goal was to build and train a custom nanoGPT model capable of accurate mathematical function calling, with a focus on multi-digit arithmetic and chain-of-thought reasoning.
 
## Key Features & Technical Achievements
 
- **Custom tool-calling:** a framework that lets the nanoGPT model execute custom function calls for arithmetic operations.
- **4-digit arithmetic accuracy:** the model was trained to handle complex mathematical operations with numbers up to four digits.
- **Pipeline optimization:** re-engineered and optimized the Python data pipelines to resolve truncation errors that occurred during multi-digit processing.
- **Overfitting diagnostics:** analyzed training and validation loss curves to diagnose and mitigate overfitting, improving the reliability of the model's chain-of-thought reasoning.
## Context within Broader Research
 
This project served as the **v1 prototype** for calculator tool-calling research at the DNU Lab. The solutions developed here for multi-digit truncation and function calling directly informed the **v2 architecture**, which used a fine-tuned DistilGPT-2 model with STAIR-inspired hierarchical memory retrieval.
 
## Tech Stack
 
- Python
- nanoGPT architecture
## Authors
 
| Author | GitHub |
|---|---|
| Rayyan Faiz Madraswala | [@R1Kexpress](https://github.com/R1Kexpress) |
| Biruk Kebede | [@kebedeb](https://github.com/kebedeb) |
 
Contribution history is available on the [contributors graph](https://github.com/R1Kexpress/nanoGPT-tool/graphs/contributors).
 
## Acknowledgements
 
Built on [nanoGPT](https://github.com/karpathy/nanoGPT) by Andrej Karpathy (MIT License).
 
