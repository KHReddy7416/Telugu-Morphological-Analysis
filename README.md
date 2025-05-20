# Telugu Morphological Analysis

This repository contains files related to Natural Language Processing tasks performed on a Telugu Wikipedia corpus. The assignment includes text preprocessing, stopword removal, frequency analysis, and visualizations.

## File Overview

| Filename                    | Description |
|----------------------------|-------------|
| `corpus.txt`               | Raw Telugu Wikipedia text corpus (unprocessed) |
| `cleanCorpus.txt`          | Cleaned version of the corpus after basic preprocessing |
| `removedStopword.txt`      | Corpus with stopwords removed |
| `stopwordList.txt`         | List of Telugu stopwords used for filtering |
| `sentence-corpus.txt`      | Sentence-tokenized version of the corpus |
| `sentence-stats.txt`       | Sentence-level statistics (e.g., length, word count) |
| `wordUnigramFreq.txt`      | Word-level unigram frequency table |
| `wordBigramFreq.txt`       | Bigram (2-word) frequency table |
| `Hemanth_1063_NLP.ipynb` | Jupyter Notebook containing full NLP analysis, code, and plots |
| `NLP1.png`, `NLP2.png`     | Output visualizations generated from the analysis |

## Main Tasks Performed

- Text cleaning and normalization
- Stopword removal
- Sentence segmentation
- Word and bigram frequency analysis
- Visualization of results using plots


```bash
jupyter notebook "Hemanth_1063_NLP.ipynb"
