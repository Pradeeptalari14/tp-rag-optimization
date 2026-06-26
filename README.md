# Vector RAG Optimizer Studio

This repository contains the target configuration and SRE runtime files compiled by the **Vector RAG Optimizer Studio** dashboard module.

## 🚀 Description
Configure advanced RAG pipelines. Optimize document embedding models, text chunking sizes, and vector database indexing schemas.

## 🛠️ Specification Matrix
- **Primary Configuration File**: `/config/rag/rag_config.json`
- **Execution Command**: `cat rag_config.json`
- **Validation Command**: `jq . rag_config.json`

## 📋 How to Run & Validate

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeeptalari14/tp-rag-optimization.git
   cd tp-rag-optimization
   ```

2. **Run Execution Target:**
   ```bash
   cat rag_config.json
   ```

3. **Verify Runtime Stability:**
   ```bash
   jq . rag_config.json
   ```

## 🔐 Security & Best Practices
* **Secret Isolation**: Use organization-level secrets (or SSM parameter hooks) rather than hardcoded environment variables inside files.
* **Pull Request Lifecycles**: Protect default branch merges with validation checks before merging code changes.
