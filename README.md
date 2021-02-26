# coRPysprofiling 

![](https://github.com/eboylestanley/corpysprofiling/workflows/build/badge.svg) [![codecov](https://codecov.io/gh/eboylestanley/corpysprofiling/branch/main/graph/badge.svg)](https://codecov.io/gh/eboylestanley/corpysprofiling) ![Release](https://github.com/eboylestanley/corpysprofiling/workflows/Release/badge.svg) [![Documentation Status](https://readthedocs.org/projects/corpysprofiling/badge/?version=latest)](https://corpysprofiling.readthedocs.io/en/latest/?badge=latest)

Package  for EDA and EDV on text

## Installation

```bash
$ pip install -i https://test.pypi.org/simple/ corpysprofiling
```

## Features

- TODO

## Dependencies

- TODO

## Usage

- TODO

## Documentation

The official documentation is hosted on Read the Docs: https://corpysprofiling.readthedocs.io/en/latest/

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/eboylestanley/corpysprofiling/graphs/contributors).

### Credits

This package was created with Cookiecutter and the UBC-MDS/cookiecutter-ubc-mds project template, modified from the [pyOpenSci/cookiecutter-pyopensci](https://github.com/pyOpenSci/cookiecutter-pyopensci) project template and the [audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage).
# DSCI524_Group13

[package name] is an open-source library designed to bring exploratory data analysis and visualization to the domain of natural language processing. Functions in the package will be used to provide some elementary statistics and visualizations for a single text corpus or provide functions to compare multiple corpora with each other.

Some specific functions include:

- `corpus_analysis`: `corpus analysis` will generate a statistical report about the characteristics of a single corpus (e.g. unique word count, average word/sentence length, top words used, topic analysis).
- `corpus_viz`: `corpus_viz` will generate relevant visualizations of a single corpus (e.g. word cloud, histograms for average word/sentence length, top words used).
- `corpora_compare`: Given two or more corpora, `corpora_compare` will find similarity (e.g, Euclidean distance or cosine similarity) between each pair of corpora.
- `corpora_best_match`: Given a reference document and two or more corpora, `corpora_best_match` will rank the corpora in the order of most relevance to the reference document.

To our knowledge, while [`wordcloud`](https://pypi.org/project/wordcloud/) library generates wordcloud visualization for a given corpus, there is no general-purpose library for exploratory analysis and visualization of a text corpus in Python ecosystem. There are several advanced libraries for comparing similarities between different corpora: most notably, [`gensim`](https://pypi.org/project/gensim/) provides similarity comparison between large corpora using word embeddings. We believe that [package name] will provide some useful functionality for exploratory analysis and visualization and help bridge the gap between elementary text analysis to more sophisticated approaches utilizing word embeddings.
