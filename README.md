# App Review Traceability using Large Language Models (LLMs)

## 📖 Overview
This repository contains research code, datasets, and results from a project on automating traceability between user app reviews and source code. The system uses Large Language Models (LLaMA 3 8B, Gemma 3 4B, Mistral 7B) and Retrieval-Augmented Generation (RAG) to connect **user feedback → GitHub issues → source-code components**.

## ⚙️ Project Phases
| Phase | Description | Status |
|-------|--------------|--------|
| **Phase 1** | Classify app reviews into comment categories (Information, Bug, Performance) | ✅ Completed |
| **Phase 2** | Link classified reviews to GitHub issues for contextual enrichment | 🔄 In Progress |
| **Phase 3** | Trace GitHub issues to corresponding source code classes and methods | ⏳ Planned |

## 🧠 Method Summary
- **LLM Classification:** Categorized app reviews using fine-tuned LLMs.  
- **Semantic Linking:** Used vector similarity and RAG to match reviews to GitHub issues.  
- **Graph Traceability:** Constructed a hierarchical mapping between user feedback and code structure.


## 🧰 Tech Stack
- Python (PyTorch, Transformers, Sentence-Transformers)
- FAISS / ChromaDB for embeddings
- Neo4j for graph linking
- Jupyter Notebooks for experiments



## 🧾 Citation
If you reference this repository in your research or report:

@misc{neupane2025traceability,
  title={App Review Traceability using Large Language Models},
  author={Neupane, Nirbhik and Islam, Md Rakibul},
  year={2025},
  howpublished={GitHub repository},
  url={https://[(https://github.com/nirbhikneup/review2code-llm)]
}


---
**Author:** Nirbhik Neupane  
**Mentor:** Dr. Md Rakibul Islam  
**Institution:** Lamar University, Department of Computer Science  

