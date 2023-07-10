# Convolve-Epoch-1-2022

To pre-process the data and make it ready for the deep learning model, all words were transformed into lower case and punctuation marks were removed. Then single character words were removed as they do not provide any relevant information about the log statements.

Then the words were transformed into encoding vectors.

The encoding vectors were then passed through our model.

Model: trainable embedding layer --> layer which computes the average of all embedding vectors of the given sample --> softmax layer which classifies log statement as normal or abnormal.

