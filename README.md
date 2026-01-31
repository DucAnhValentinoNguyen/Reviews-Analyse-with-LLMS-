# Analysing Reviews using LLMs

Goal: prototype a chatbot app addressing diverse inquiries using LLMs.

We use a pre-trained LLM to classify the sentiment of the five car reviews in the dataset, then evaluate the classification accuracy and F1 score of predictions.

We will also deal with spanish reviews, where we extract and pass the first two sentences of the first review in the dataset to an English-to-Spanish translation LLM, then calculate the BLEU score to assess translation quality, using the content in reference_translations.txt as references.
