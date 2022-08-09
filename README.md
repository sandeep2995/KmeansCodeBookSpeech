# KmeansCodeBookSpeech
generates speech-based codebook using K-means

All the following files and graphs are in "K-means/" directory

config.h---> configuration file to set various things such as delimiter, filename, thresold distortion allowed, precision of the code vectors, etc.

kmeans---> implements k means algorithm on universe of cepstral coefficient vectors.

set the values in config.h and run the project.

distortion will be saved in "logdistortion.txt" (average distortion per cluster)

select all and paste in excel sheet to see the graph of average distortion Vs. number of iterations.(see various graphs kmeans1.png, kmeans2.png, kmeans3.png and kmeans4.png attached)

"codebook.txt" contains the final code vectors.

"logclustersize.txt" contains intermediate result indicating number of vectors associated with each cluster after every iteration.

Note:
Various extra methods are provided in the program which you may use based on your interest


P.S:

Program that we used to compute the universe of cepstral coefficients also attached.
"locep.txt" contains log file while generating the universe.
"cep.txt" contains the universe of cepstral coeffients separated by space.
"ScaledInpSpeech.txt" contains latest scaled input speech sample values
