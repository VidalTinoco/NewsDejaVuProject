# Article Comparison: An Analysis of News Deja Vu Performance

**Contributors** : Kelsey Strachan, Vidal Mendoza Tinoco, Amali Jayatileke

### Package dependencies

To run the notebooks, install the following Python packages:

```bash
!pip install transformers datasets seqeval torch
!pip install seqeval --upgrade
```

### Project Overview

This project replicates and extends the findings of the paper "News Déjà Vu: Connecting Past and Present with Semantic Search" by Franklin et al. (2024). We benchmarked the performance of the Custom Historical NER model against several state-of-the-art models on historical news texts, analyzing performance variations across different experiments.

### Notebook structure

**Experiment 1:** Performance sensitivity of the Custom Historical NER model to corpus size

**Experiment 2:** Comparison of Custom Historical NER against alternative transformer-based models

**Experiment 3:** Evaluation of Custom Historical NER performance across different news topics

**Experiment 4:** Hyperparameter tuning of Custom Historical NER (batch size, learning rate, epochs)

### Sources

- Research article: 
B. Franklin, E. Silcock, A. Arora, T. Bryan, and M. Dell, "News Deja Vu: Connecting Past and Present with Semantic Search," arXiv preprint arXiv:2406.15593, Jun. 2024. [Online]. Available: https://arxiv.org/abs/2406.15593​arXiv

- Research GitHub: 
https://github.com/dell-research-harvard/newsdejavu

- Custom Historical NER pre-trained model:
https://huggingface.co/dell-research-harvard/historical_newspaper_ner

- Training dataset:
https://huggingface.co/datasets/dell-research-harvard/newswire