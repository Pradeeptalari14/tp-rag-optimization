[![Ecosystem](https://img.shields.io/badge/Portfolio%20Ecosystem-341%20Studios-6366f1.svg)](https://pradeeptalari.me/projects/)
[![Architecture DAG](https://img.shields.io/badge/Architecture-DAG%20%26%20Course-10b981.svg)](https://pradeeptalari.me/tools/repo-learning/)

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

---
*Synchronized with [Vector RAG Optimizer Studio Studio](https://pradeeptalari.me/tools/rag-optimization/) & [Repository Learning DAG](https://pradeeptalari.me/tools/repo-learning/) — [Talari Pradeep Portfolio](https://pradeeptalari.me)*
