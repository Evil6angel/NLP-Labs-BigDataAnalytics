# Lab 04 – Machine Translation, POS Tagging & Named Entity Recognition

- Machine Translation: fine-tuned MarianMT (or similar HF model) for French → English, tested on a given set of sentences + evaluation on custom inputs.

- POS Tagging: tokenization + POS tagging using NLTK and spaCy; comparison of tagset formats and differences in output between libraries.

- Named Entity Recognition (NER): applied spaCy’s pre-trained NER pipeline to a set of sentences, extracted entities with type labels, analyzed errors/misclassifications.

## Tech: Python, Hugging Face Transformers, MarianMT, spaCy, NLTK