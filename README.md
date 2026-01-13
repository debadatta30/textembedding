# Text Embeddings Tutorial

A complete guide to understanding and using text embeddings with SentenceTransformer.

## What's Inside

- Text embedding basics and concepts
- Cosine similarity explained with scoring ranges
- Semantic search engine implementation
- FAQ matching for customer support
- Practice exercises with movie recommendations

## Setup

Install required dependencies:

```bash
pip install sentence-transformers scikit-learn numpy pandas matplotlib seaborn
```

## Usage

Open `text_embeddings_tutorial.ipynb` in Jupyter and run the cells sequentially.

The notebook uses `all-mpnet-base-v2` model, which downloads automatically on first run (~420MB, cached locally).

## Model Information

- **Model**: all-mpnet-base-v2
- **Embedding Dimensions**: 768
- **Download Size**: ~420MB
- **No API key required** - runs completely offline


## Key Concepts

**Text Embeddings**: Numerical representations of text that capture semantic meaning. Think of them like GPS coordinates for concepts in "meaning space."

**Cosine Similarity**: Measures how close two embeddings are by calculating the angle between them. Returns a score from 0 (unrelated) to 1 (identical).

**Why all-mpnet-base-v2**: Open-source, runs locally, no API costs, better semantic understanding than smaller models.

## Next Steps

After completing the tutorial:
- Experiment with your own text data
- Build a recommendation system
- Create a chatbot with memory
- Try multilingual embeddings
- Explore other embedding models

## Requirements

- Python 3.10
- ~500MB free disk space for model caching
- Jupyter Notebook or JupyterLab
