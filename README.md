# Edible Insect Research Bibliometric Analysis

This repository contains the complete dataset and analysis code for a comprehensive bibliometric study examining the rapidly evolving landscape of edible insect research from 2015 to 2025. The analysis maps 1,585 scientific publications from the Scopus database to reveal research trends, thematic evolution, and global patterns in entomophagy science.

## 📊 Analysis Overview

This study employs advanced analytical techniques to examine:

- **Publication Growth**: Temporal trends showing 3-fold increase from 88 to 247 papers annually
- **Thematic Structure**: Six dominant research themes identified through Non-Negative Matrix Factorization
- **Network Analysis**: Keyword co-occurrence patterns revealing three principal research clusters
- **Geographic Patterns**: Country-level research contributions with Thailand, USA, and China leading
- **Topic Evolution**: Shift from foundational research to applied sustainability and consumer studies

  ## 🔧 Methodology

### Data Processing
- **Source**: Scopus database (January 2015 - August 2025)
- **Search Query**: `TITLE-ABS-KEY("edible cricket" OR "*Acheta domesticus*" OR "cricket flour" OR "insect protein" OR entomophagy)`
- **Preprocessing**: Lowercase conversion, punctuation removal, stop-word elimination, lemmatization

### Analytical Techniques
- **Keyword Co-occurrence Networks**: NetworkX for relationship mapping
- **Topic Modeling**: Non-Negative Matrix Factorization (NMF) for theme extraction
- **Clustering Validation**: K-means clustering with Principal Component Analysis (PCA)
- **Temporal Analysis**: Annual publication trends and thematic evolution


## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab


## 📚 Citation

If you use this dataset or code
