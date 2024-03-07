# Cosine-vs-Conceptual-Similarity-in-BERT-model-

**Conceptual Similarity :**
1) Uses the BERT model (BertForSequenceClassification) from the Hugging Face Transformers library.
2) Tokenizes the input text and encodes it using the BERT tokenizer.
3) Calculates the embeddings for both the input text and the texts in the dataset using the BERT model.
4) Measures similarity between the input embeddings and the dataset embeddings using cosine similarity.
5) Determines the label or category based on the highest cosine similarity score.
6) Relies on the cosine_similarity function from scikit-learn for similarity calculation.

**Cosine Similarity :**
1) Uses the Sentence Transformer library.
2) Loads a pre-trained Sentence Transformer model (paraphrase-MiniLM-L6-v2).
3) Embeds both the input text and the texts in the dataset using the Sentence Transformer model.
4) Calculates similarity scores between the input embedding and the dataset embeddings using cosine similarity.
5) Determines the label or category based on the most similar texts.
6) Uses functions provided by the Sentence Transformer library (encode and pytorch_cos_sim) for embedding and similarity calculation.
7) In summary, both snippets achieve similar functionality but use different libraries and models for text embedding and similarity calculation. The choice between them depends on factors such as model preference, performance requirements, and ease of integration with existing codebases.
