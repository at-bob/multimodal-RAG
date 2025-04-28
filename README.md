# multimodal-RAG

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
│   ├── gold_test_set.json       # Your gold standard test dataset
│   └── evaluation_results.ipynb # Jupyter notebook to evaluate system performance
└── docs/
    └── report.md                # Your final report, evaluation, and analysis
