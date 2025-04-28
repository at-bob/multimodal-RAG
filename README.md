# Multimodal RAG Video QA

An end-to-end multimodal retrieval-augmented generation (RAG) system that answers user queries by retrieving relevant video segments based on both audio and visual embeddings.

## Project Structure

multimodal-rag-video-qa/
├── README.md                    # Overview, instructions, and quick start guide
├── requirements.txt             # Python dependencies
├── data/
│   ├── transcripts/             # Store extracted audio transcripts
│   ├── frames/                  # Extracted keyframes from video
│   └── embeddings/              # Generated embeddings
├── src/
│   ├── data_processing/         # Scripts/notebooks for data extraction & processing
│   ├── embeddings/              # Scripts for generating embeddings
│   ├── retrieval/               # Implementation of FAISS, pgvector, TF-IDF, BM25
│   └── app/                     # Streamlit UI application code
├── evaluation/
│   ├── gold_test_set.json       # gold standard test dataset
│   └── evaluation_results.ipynb # Jupyter notebook to evaluate system performance
└── docs/
    └── report.md                # final report, evaluation, and analysis

## Setup Instructions
```bash
pip install -r requirements.txt