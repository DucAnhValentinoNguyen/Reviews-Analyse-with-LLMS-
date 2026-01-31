# Analysing Reviews using LLMs

We use a pre-trained LLM from Hugging Face to classify the sentiment of the five car reviews in the dataset, then evaluate the classification accuracy and F1 score of predictions.

We will also deal with spanish reviews, where we extract and pass the reviews in the dataset to an English-to-Spanish translation LLM, then calculate the BLEU score to assess translation quality, using the content in reference_translations.txt as references.
