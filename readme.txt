1 Overview of SPCNV
SPCNV: A shortest path-based approach for copy number variations detection from next-generation sequencing data.
In order to verify the validity of SPCNV,we use it to detect simulation data and real data compared with several existing methods,which 
proves to be a very effective and reliable tool.
2 Usage
2.1 Operating environment
Our software is running on Linux system.It is developed using R and Python language.The users 
need to install the SAMtools,R and Python to build environment before running the software.
We need to install the R package(readr,dbscan,stringr and proxy) and Python packages(pysam,numpy and numba)
R version: 3.6.0
Python version: 3.5.2
2.2 Input
The users need to input a bam file and a reference genome file. 
The reference genome that is a fasta format file.
2.3 parameter settings
The parameters are saved in the config file.The users can set relevant parameters according to needs and apply them to different scenarios.
The structure of the config file includes two columns of data,which represent binsize and k.
The values given in the file are default parameters.
2.4 Run command
sh run.sh
2.5 Output
The output is saved in the result text file.
3 Application
We provide an application example for the user to further use the software.

