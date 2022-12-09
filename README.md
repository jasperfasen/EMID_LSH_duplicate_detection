# EMID_LSH_duplicate_detection

This repository contains a code for product duplicate detection based on the extracted modelID process (EMID) and LSH.

The code imports a data sets on TV's. For each TV it extracts the modelID from the product title and identifies it to be a duplicate. After that model words have been extracted from the product's title and features, a binary vector matrix is made. This binary vector matrix functions as an input for LSH that returns candidate pairs. Given the candidate pairs from EMID and LSH, clusters are found through agglomerative clustering.
