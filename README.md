# LangChain & LlamaIndex Studio

This repository contains the target configuration and SRE runtime files compiled by the **LangChain & LlamaIndex Studio** dashboard module.

## 🚀 Description
Orchestrate application workflows using LangChain and LlamaIndex. Generate prompt routing templates, hybrid query pipelines, and document loaders.

## 🛠️ Specification Matrix
- **Primary Configuration File**: `/src/pipelines/pipeline.py`
- **Execution Command**: `python3 pipeline.py`
- **Validation Command**: `python3 -m pytest`

## 📋 How to Run & Validate

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeeptalari14/tp-langchain-llamaindex.git
   cd tp-langchain-llamaindex
   ```

2. **Run Execution Target:**
   ```bash
   python3 pipeline.py
   ```

3. **Verify Runtime Stability:**
   ```bash
   python3 -m pytest
   ```

## 🔐 Security & Best Practices
* **Secret Isolation**: Use organization-level secrets (or SSM parameter hooks) rather than hardcoded environment variables inside files.
* **Pull Request Lifecycles**: Protect default branch merges with validation checks before merging code changes.
