# Twitter_profanity_detection-nlp for beginers

This repository contains a simple approach for NLP Classification task- detecting profanity in twitter data. The model predicts hate speech in text. The data is sufficiently preprocessed for model training but there are certain preprocessing tasks 
which should be taken in consideration -
1. Emojis in uint8 format were present, which were deleted in the code. They can be used by converting into texts.
2. There is imbalance in labels of dataset. This is not suitable for model, as it turns to make  biased learning.
3. We can use Transfer learning or huggingface transformers for better classification.

The data is preprocessed using TensorFlow libraries, split into train and test sizes. 
A simple model with embeddings layer , lstm layers, gru layers, and dense layers was created with binary_crossentropy as loss function , optimizer- adam, and accuracy as metrics.
