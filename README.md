# LLM Project to Build and Fine Tune a Large Language Model

The aim of this project is to provide a comprehensive understanding and practical experience in working with Large Language Models (LLMs).

## Overview
In today's data-driven world, the ability to process and generate natural language text at scale has become a transformative force across industries. Large Language Models (LLMs) represent a cutting-edge advancement in natural language processing, enabling businesses to extract valuable insights, automate tasks, and enhance user experiences. By harnessing the power of LLMs, organizations can improve customer service, automate content creation, and gain a competitive edge in the digital landscape.

This project builds the foundation for Large Language Models by diving deep into the details of their inner workings. Moreover, It shows how to optimize their use through prompt engineering and fine-tuning techniques such as LoRA.

Prompt engineering techniques involve crafting specific instructions or queries given to the language model to influence its output will be introduced to guide LLMs in generating desired responses through zero-shot, one-shot, and few-shot inferences.

## Data
- The dialogue summarization exercises in this project utilize the knkarthick/dialogsum dataset from the Hugging Face library.
- For the purpose of demonstrating the development of a chatbot, data about apparel and paper products is provided. This dataset includes textual information about various apparel items and paper products.

_Data is not included in this repository._

## Approach
- Introduction to LLMs and Basics: ○ Explanation of RNNs, transformers, attention mechanism, and Large Language Models (LLMs). ○ Illustration of use cases, including text generation, to establish foundational knowledge.
- Prompt Engineering: ○ Introduction to prompt engineering techniques, including zero, one, and few-shot inferences.
- Dialogue Summarization Task: ○ Implementation of prompt engineering on a dialogue summarization task, showcasing practical application.
- Fine Tuning and PEFT: ○ Implementing full fine-tuning and parameter-efficient fine-tuning (PEFT) on dialogue summarization.

○ Model evaluation using ROUGE metrics for performance assessment.
- RLHF (Reinforcement Learning from Human Feedback): ○ Explanation and exploration of the RLHF concept
- Retrieval Augmented Generation (RAG): ○ Practical implementation of RAG using OpenAI's GPT3.5 for creating a chatbot.
- Development of Chatbot Application: ○ Step-by-step guide on building a functional chatbot application for online shopping using RAG.

Cost Breakdown

Components
- Streamlit Chatbot with Opena AI and experimentation in OpenAI

Cost Breakdown as of January 17, 2025 The cost might have been updated, it is recommended to go through the following pricing pages to come up with updated guessestimates. Open AI Pricing https://openai.com/api/pricing/

Componen        Description               Usage                     Estimated Cost t

API Calls    OpenAI API          Models used: - GPT-3.5      Total Estimated Usage:- 100 (GPT-4 Turbo and    Turbo (16K context):        queries- Avg 1,000 GPT-3.5 Turbo)      $0.0015 per 1K tokens       tokens/query for RAG and         (input), $0.002 per 1K chatbot             tokens (output)- GPT-4      Cost Estimate:- GPT-3.5 responses           Turbo (8K context): $0.01   Turbo: (input: $0.15, output: per 1K tokens (input),      $0.20)- GPT-4 Turbo: (input: $0.03 per 1K tokens         $1.00, output: $3.00) (output)

Total Estimated Cost: ~$5 - $10 per project.

Recommendation: GPT-3.5 Turbo is more cost-effective for high-volume interactions, while GPT-4 Turbo provides superior responses but at a higher cost. Proper token usage monitoring is essential to optimize costs.

Experimentation should balance performance needs with budget constraints.For cost efficiency, consider using GPT-3.5 Turbo for routine chatbot interactions and GPT-4 Turbo for complex or critical tasks requiring higher accuracy.

## Tech stack
➔ Language: Python 3.8 ➔ Libraries: transformers, datasets, torchdata, torch, streamlit, openai, langchain, unstructured, sentence-transformers, chromadb, evaluate, rouge_score, loralib, peft

## How to run
```bash
pip install -r Project_Code/requirements.txt
```
Notebooks: [`llm_labs.ipynb`](Project_Code/llm_labs.ipynb)

## Project structure
```
.gitignore
Project_Code/
  llm_app.py
  llm_labs.ipynb
  readme.md
  requirements.txt
README.md
```

## Credits
Based on a ProjectPro guided project.
