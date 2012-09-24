Standardized-Lossy-Compression-Algorithm
========================================

Advanced Audio Coding is standardized lossy compression and encoding scheme for audio signal which is taken as one dimensional serial data.

This coding scheme starts with transforming input data with Modified Discrete Cosine Transform algorithm (MDCT).


1. MDCT : MDCT explores energy compaction property of Discrete Cosine Transform algorithm with some additional features. It comprises of Discrete Sine Tranform and Discrete Cosine Transform algorithms.
          
          
2. Non-Linear Quantization Algorithm : This is the 'lossy' part of this coding scheme.


3. HUFFMAN coding : This is a type of entropy coding scheme for lossless data compression. It has following parts:


                  i)  QUICK SORT : Sorting data to calculate probability of each data representation.
                  
                  
                  ii) Generating Huffman tree using probabilities.