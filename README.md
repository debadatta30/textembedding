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
- **Similarity Scoring** (all-mpnet-base-v2):
  - 0.9+ = Nearly identical meaning
  - 0.75-0.89 = Very similar
  - 0.5-0.74 = Somewhat related
  - 0.3-0.49 = Loosely related
  - <0.3 = Different topics or unrelated

## Examples Included

1. **Example 1**: Your first embedding - converting a word to a vector
2. **Example 2**: Embedding complete sentences
3. **Example 3**: Comparing similar vs different topics
4. **Example 4**: Different words, same meaning
5. **Example 5**: Similarity heatmap visualization
6. **Example 6**: Semantic search engine
7. **Example 7**: FAQ matching for chatbots

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

- Python 3.7+
- ~500MB free disk space for model caching
- Jupyter Notebook or JupyterLab
