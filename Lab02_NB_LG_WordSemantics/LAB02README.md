# Lab 02 – Naïve Bayes, Logistic Regression (Toxicity) & Word Semantics

- Naïve Bayes (from scratch): preprocess tweets, build frequencies, priors/likelihoods with Laplace smoothing + log-probs, evaluate on held-out tweets.

- Logistic Regression (Jigsaw Toxic Comments): combine labels into Toxic vs Insult per spec, augment with emoji examples, engineer features (incl. emoji signals), train & report results.

- Word-level semantics: Deep-LSA on LinkedIn connections (TF-IDF pipeline); transformer embeddings + cosine similarity to retrieve top-5 similar comments; Word2Vec comparison.

## Tech: Python, NLTK, scikit-learn, (emoji/emot), gensim/Word2Vec, HF Transformers