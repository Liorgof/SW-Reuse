# SW-Reuse: Software Reuse Using Code Summarization and LLMs

### Final Project – B.Sc. in Software Engineering  
_Sami Shamoon College of Engineering – 2025_

## 📌 Overview
This project proposes a novel approach for improving code reuse by leveraging **Large Language Models (LLMs)** to generate natural language summaries of code snippets.  
Instead of matching code directly to user queries, we use summaries to bridge the gap between how developers search for functionality and how code is actually written.

The project evaluated several LLMs – including **CodeT5**, **DeepSeek**, and **LLaMA** – for summarizing code and retrieving relevant snippets.  
We built a pipeline to:
- Summarize thousands of Java functions from the CodeSearchNet dataset
- Compare semantic similarity between summaries and natural language queries
- Benchmark performance using metrics like Recall@K and MRR

## 🧪 Key Features
- Automatic summarization of code snippets
- Code retrieval based on semantic summary-query matching
- Evaluation against CoIR benchmark (Code Reuse Challenge – NeurIPS 2022)
- Fine-tuning and comparison of multiple LLMs

## 🛠️ Technologies Used
- Python, Pandas, NumPy
- Hugging Face Transformers
- CodeT5, DeepSeek, LLaMA
- FAISS similarity search
- GitHub Copilot, Jupyter Notebooks

## 📁 Dataset
- [CodeSearchNet](https://github.com/github/CodeSearchNet)
- Focus on Java functions with Javadoc descriptions

## 📊 Evaluation
- Metrics: **Recall@K**, **MRR**
- Baseline comparison against CoIR challenge models
- DeepSeek showed the best summarization quality in our evaluation

## 📄 Authors
- Lior Gofman   
- Nir Knimach   
Supervisor: Dr. Marina Litvak

## 📚 License
This project is academic and research-oriented. For inquiries, please contact the authors.
