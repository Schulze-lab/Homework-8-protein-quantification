# Assignments Week 7
# Introduction
The goal of this assignment is to perform a label-free, relative quantification of protein abundances for a publicly available datasets of Streptococcus mutans. This analysis should result in a list of differentially abundant proteins for different strain comparisons. In the lab, we will go over the usage of the quantification engine FlashLFQ within the Python framework Ursgal, but you are welcome to use any other quantification tool that you see fit.
# Input data
You can use the .mzML files from the PXD019825 datasets and the protein database search results that you have obtained in Week 6. These files should be in your user folder on the Oedipus server.
# Tasks and output files
1)	Perform a label-free, relative quantification for the dataset PXD019825 using the WT vesicles samples as control condition. Log2 fold changes and corresponding posterior error probabilities should be obtained for the various condition comparisons (with WT vesicles as control condition).
2)	Create volcano plots for comparing each mutant strain vesicle proteome to the WT vesicle proteome. Volcano plots display differentially abundant proteins based on the log2 fold changes and -log10 PEP.
3)	Make sure to comment your code, so that others can read and understand it easily. 
4)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
5)	Commit your scripts to your GitHub Classroom repository. Do NOT commit large input files (like .raw, .mzML, etc)! The result files should be stored in your folder on the Oedipus server.
# Submission
You must submit the assignment through GitHub Classroom by 8 am ET on Mar 06 to get full credit.

