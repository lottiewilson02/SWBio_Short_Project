# Simple Tools for DNA Sequence Investigation
This is a simple pipeline produced to allow investigation of DNA sequences, using the Python coding language. Produced for use with _Rubus idaeus_ (red raspberry) sequences, to a comercially important crop with little known surrounding the features of the genomes, it is also effective with a wide range of DNA sequences from other organisms, although it has only been tested with eukaryotic DNA sequences so far. 

## Features
Use of this code will allow the following functions to be carried out for your required DNA sequence:
- Complementation
- Reverse complementation
- Transcription
- Back transcription
- Translation
- Calculation of the percentage GC content within the sequence
- Alignment of multiple sequences (requires a different input to the above features, a file containing multiple DNA sequences)

## How to run
1. Download the script from this repository.
2. Ensure all the modules at the start of the script are successfully loaded. The script will require BioPython to run correctly - if not already installed this can be carried out using the "pip install biopython" command in the command line. The script will also require installation of MAFFT. If not already installed, this can also be completed in the command line using "conda install -c bioconda mafft".
3. For the "simple tools for sequence investigation" section, input your chosen DNA sequence into the "DNA_input" line.
4. The script can then be run for any of the desired functions. The output for each function will be displayed underneath the respective section of the code.
5. For the GC%







The script was tested using the "Sequences_Fasta2.fa" file in this repository, with a segment of the "Glen Ample" sequence for the testing of the complementation to the GC content functions section. This file can be downloaded for use alongside the script
