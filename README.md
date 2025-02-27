# Assignments Week 3
# Introduction
The goal of this assignment is to mimic part of a typical proteomics sample processing workflow on the bioinformatic side. The two steps that will be covered by this assignment are (i) protein digestion, and (ii) chromatographic separation of peptides.
# Input data
The reference proteome of Streptococcus mutans should be used as input file. The same .fasta file as in Assignment 1 can be used.
# Tasks and output files
1)	Perform an in silico digest of all proteins within the input .fasta file. Use trypsin as proteolytic enzyme. You can use existing modules (like pyteomics’ parser.cleave() function) or write your own function that takes into account tryptic cleavage sites (cleaves after K and R, unless followed by P).
2)	For all unique peptide sequences resulting from the digest, determine the percentage of peptides that could originate from different proteins (i.e. peptides that are not specific to a single protein). These peptides are called non-proteotypic.
3)	Does the length of a peptide have an influence on whether that peptide is likely proteotypic or not? Answer this question by plotting either the length distribution of all non-proteotypic peptides, or the percentage of non-proteotypic peptides for each peptide length (or some other creative way that you can come up with).
4)	Make sure to comment your code, so that others can read and understand it easily. 
5)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
6)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
Additional MS student tasks (bonus credit for BS students)
7)	Calculate the theoretical retention time (on a standard C18 RP-HPLC, assuming a maximum retention time of 60 min) for all unique peptides using a machine learning based model (e.g. DeepLC, or AutoRT; if neither works for you, you can use an additive model such as pyteomics’ achrom module instead). Plot the resulting retention times.
# Bonus task for MS students
8)	When plotting the retention time of all peptides (task 7), take into account that peptides elute ideally with a Gaussian distribution (see image below). Let’s assume that the peak width is 30 seconds, and the maximum retention time is 60 min. What is the percentage of peptides that have theoretically overlapping elution peaks? How does that number of overlapping peaks change if we increase the maximum retention time to 120 min (with an increase in peak width to 35 seconds due to increased diffusion)? 

# Submission
You must submit the assignment by 8 am Feb 6 to get full credit. 
