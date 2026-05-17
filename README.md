# Enterprise RAG: Domain-Specific AI Assistant

An advanced, conversational AI chatbot workspace built and optimized for cloud notebook environments (such as Kaggle) and local Python executions. This project demonstrates the step-by-step implementation of custom system prompts, multi-turn dialogue state management, and an end-to-end Retrieval-Augmented Generation (RAG) architecture using Python and the official OpenAI API.

## 🚀 Project Overview

This system bridges the gap between generic large language models and highly localized, contextual corporate knowledge bases. The project is split into two primary phases:
1. **Domain-Specific System Prompting (Lab 9):** Implements persona-driven assistants (such as an HR Advisor and TechShop Customer Support Bot) equipped with strict operational parameters and stateful conversation memory logs.
2. **Retrieval-Augmented Generation / RAG (Lab 10):** Implements a lightweight internal file reader, paragraph tokenizer, and keyword frequency matching retrieval engine from scratch in pure Python to anchor the LLM's answers directly inside private corporate policies, effectively eliminating factual hallucinations.

---

## 🛠️ System Architecture

The workflow below illustrates how incoming user queries are dynamically paired with relevant contextual reference chunks before hitting the model endpoint:
