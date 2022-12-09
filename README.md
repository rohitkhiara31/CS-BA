# CS-BA
Scalable Product Duplicate Detection

This project attempts to find duplicate TVs across different online shops in a scalable yet accurate way. Locality senstivity hashing (LSH) is implemented on the dataset. LSH yields candidate pairs which are classified based on brand and modelID extracted from the title and the titles of the pair needs to be above a certain cosine similiarity threshold to be classified as duplicates.

The code can be run in the order of the cells. First cell contains the importing of the data, second the tuning of the threshold, and the third cell is the running of the algorithm on different number of rows per band in LSH. Programming buddy: Yassine Ben Haddou, 523321
