# InfoB473-Assignment-1
# INFO-B 473/B573 Assignment 1

## Programmer Information

Programmer made by Abdul Djama

Language: Bash

Version: 1.0

Date Submitted: September 15, 2026


## Purpose

The purpose of this script is to download the secondary human
chromosome 1 assemblies from the UCSC Genome Browser and create a
summary of the downloaded data.

The script creates the Informatics_573 directory, downloads the
secondary chromosome 1 assemblies, unzips the files, and creates
a data_summary.txt file containing information about each assembly.


## Files Needed

Info-B473assignment1.sh - The Bash script used to download and
process the chromosome 1 assemblies.

No chromosome files need to be downloaded before running the script
because the script downloads them from UCSC.


## Software Needed

- Bash
- wget
- gunzip
- ls
- head
- wc
- echo
- Internet connection


## How to Run the Script

1. Download Info-B473assignment1.sh.

2. Open a terminal.

3. Navigate to the directory containing the script.

4. Give the script permission to run:

   chmod +x Info-B473assignment1.sh

5. Run the script:

   ./Info-B473assignment1.sh

6. Wait for the script to finish downloading and processing the files.

7. The results will be located in the Informatics_573 directory
   inside the user's home directory.


## Files Created

Informatics_573 - Directory containing the downloaded chromosome
assemblies from the UCSC and the summary file.

Chromosome 1 .fa files - The unzipped secondary chromosome 1
assemblies downloaded from UCSC.

data_summary.txt - Contains detailed file information, the first
10 lines of each assembly, and the total number of lines in each
assembly.


## Data Source

UCSC Genome Browser hg38 chromosome data. From: https://hgdownload.soe.ucsc.edu/goldenPath/hg38/chromosomes/

