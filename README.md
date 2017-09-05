# FindEMAST
Algorithm to find potential CTTT EMAST sequences in any genome. User just defines name of new .xls file where the results will be written to.
Code will need to be run from a folder where the genome file is stored in .fasta format.
Code is set to search CTTT sequnces only, using the 25 nucleotide flanking sequences only and the provided motifs only. These parameters can be changed by editing the code.
Example use:
Download human chromosome 1 as a .fasta file. Place in folder named "EMAST example". Save this Python code as a .py file in teh same folder. Open the python file and run python shell. Type: "EMASTCTTT("example.xls") and hit enter. The shell will load real time results as code searches fasta file- number of sequences found and how many have the motif. Once done, go to EMAST example folder and open example.xls using excel. 
