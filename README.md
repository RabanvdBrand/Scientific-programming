# Scientific-programming
In this project FastQ files are taken and transformed into the count matrix, steps taken in a linux terminal are described in their place in the order of fuctions, but not included in the processing. Using the count matrix differential gene expression is performed on the 4 groups of 3 day old western honey bee(apis mellifera) larvae, the groups are as following:
1. Queens reared from eggs
2. Queens reared from transplanted 1 day old larvae
3. Queens reared from transplanted 2 day old larvae
4. Worker bees

Using the differentially expressed genes the following analysis steps will be performed
1. Functional enrichment
2. pathway enrichment
3. PCA
4. ASCA
5. Visualization of the structure in Cytoscape using STRING


Code is made for R and should be run in the following order
1. raw_file_processing.rds
2. QC_of_count_matrix
3. annotation_creation
4. analysis

