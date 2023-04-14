# Convolve-Epoch-1-2022

The data processing involved transforming all words into lower case, getting rid of punctuation and finally removing single character words which do not help in understanding the log statement.

Then the words were transformed into encoding vectors.

The encoding vectors were then passed through our model.

Model: trainable embedding layer --> layer which computes the average of all embedding vectors of the given sample --> softmax layer which classifies log statement as normal or abnormal.

