# Experiments with models for article bias prediction

## Dataset

Original dataset: [link](https://github.com/ramybaly/Article-Bias-Prediction)

Article of authors of original dataset: [We Can Detect Your Bias:
Predicting the Political Ideology of News Articles. Baly et al.] (https://arxiv.org/abs/2010.05338)

Dataset preprocessed with ''preprocess.ipynb'' from json to csv. After that ''dataset'' folder contains media split and dataset in csv format.

## Experiments

### Baseline model

Fine-tuning of differt BERT-like models with different losses. (''baseline models'' folder)

Models: (from Hugging Face)
- bert-base-cased
- bert-large-cased
- microsoft/deberta-v3-base

Losses:
- Crossentropy
- Focal Loss (implemented, not tested)
- MSE
- L1 (implemented, not tested)

results described in ''train_baseline_results.txt'' file.

### Media debiasing
Not implemented yet

## Article
Working on it