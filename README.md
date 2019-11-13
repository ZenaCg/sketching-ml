# Sketching with ML

Yunchieh Chang, cyunchie@ucsd.edu

## Abstract

In this project, we demonstrate handwriting generation using the Graves handwriting model which is constructed with three layers of LSTM cells, an attention mechanism digests an one-hot encoding of the sentence, and a mixture density network for adding some nature randomness. We generate four different handwritten letters with different bias settings written by four children to Santa Claus. Each letter is divided into several pieces of 20-character-long sentences to maintain accuracy. 

## Files

Briefly decribe the files that are included with your repository:
- santa1.txt santa2.txt santa3.txt santa4.txt - input text data
- letterGenerator.ipynb - code that generates “hand-drawn” outputs using handwriting-rnn 
- /saved - pretrained model
- /output_images - generated handwriting

## Results

- Results.pdf - A file with generated handwriting.
- /output_images - output handwriting from the project, in png format.


## Notes

Add any implementation notes or details on how to repeat your work.
- The input text is divided into peices of 20-character-long sentences to maintain accuracy.
- The model is automatically built and intialized everytime when a new 20-character-long sentence is fed into the program.
