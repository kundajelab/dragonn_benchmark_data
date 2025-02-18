# Standardized Datasets for Applying Deep Learning Tricks and Benchmarking Models
Deep learning methods and unit tests for standardized datasets. Used as a benchmark for new approaches. 

1 .datasets from the GECCO variant scoring project, varying levels of difficulty 

  a. GC-balanced 1 positive: 1 negative 
  
  b. GC-balanced 1 positive: 5 negatives
  
  c. Dinucleotide-balanced 1 positive: 1 negative 
  
  d. Dinucleotide-balanced 1 positive: 5 negatives 
  
  e. ENCODE universal negatives 
  
  f. Differential peaks within the GECCO task set (i.e. sample V576 vs union of peaks from other samples). 
  
  g. V576.bed.gz --> original bed file for sample, including signal strength values for regression models.

  h. Dinucleotide-shuffled negatives at a ratio of 1 positive: 1 negative (train/test/validate.dinucshuffled.negatives.fasta.gz) 
