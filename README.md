# Twitter_profanity_detection-nlp for beginers

This repository contains a simple strategy for detecting profanity in twitter data using natural language processing (NLP). Hate speech in text is predicted by the model. For a simple nlp model, the data has been suitably preprocessed.
The data is separated into train and test sizes and preprocessed using TensorFlow libraries.
A simple model with embeddings layer , lstm layers, gru layers, and dense layers was created with binary_crossentropy as loss function , optimizer- adam, and accuracy as metrics.

There were some preprocessing jobs that were not used in the above notebook that should be considered: 
1. Emojis in uint8 format were present, but they were removed from the data. They can be converted into text and used.
2. The dataset's labels are unbalanced. This is not appropriate for a model because it leads to biassed learning.
3. To improve categorization, we can utilise transfer learning or huggingface transformers.
