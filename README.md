## Word Recognition Using Deep Convolution Neural Network

– Trained a deep CNN model that can help in recognising a word, i.e. given a word-image as input, the model yields a
representation that can help in recognising the word from a ’lexicon’ of words.

– **Used:-** Sequential model - Keras, Alpha & Omega representation, Neural Networks.

### Representations of the word
***There are two representations for a word:-***

**1) Alpha representation:-** This is based on the claim that a word can be represented in terms of occurences of characters in various segments of image.

**2) Omega representation:-** This is based on the claim that a word can be represented in terms of count of 11 primitve shapes present in various segments of image. The 11 shapes are: ***ascender, descender, left small semi-circle, right small semi-circle, left large semi-circle, right large semi-circle, circle, vertical line, diagonal line, diagonal line at a slope of 135 degrees, and horizontal line***. These have been shown in figure.
