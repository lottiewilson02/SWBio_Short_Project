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

## How to run - Simple tools for sequence investigation
1. Download the script from this repository.
2. Ensure all the modules at the start of the script are successfully loaded. The script will require BioPython to run correctly - if not already installed this can be carried out using the "pip install biopython" command in the command line.
3. For the "simple tools for sequence investigation" section, input your chosen DNA sequence into the "DNA_input" line.
4. The script can then be run for any of the desired functions. The output for each function will be displayed underneath the respective section of the code.
5. For the GC% result, the output is displayed without units, however it is a percentage value of the sequence.

## How to run - Alignment of multiple sequences
1. Download the script from this repository.
2. Ensure all the modules at the start of the script are successfully loaded. The script will require BioPython to run correctly - if not already installed this can be carried out using the "pip install biopython" command in the command line. The script will also require installation of MAFFT. If not already installed, this can also be completed in the command line using "conda install -c bioconda mafft".
3. Create the file containing the sequences required for alignment. This must be in fasta format!
4. Edit the URL link to reach the correct file containing the sequences. This may also be edited to import the file from a directory.
5. Edit the filename code to your desired file name - ensure this is consistent throughout the script if edited.
6. Following this, the script will display the titles of each sequence - check this to ensure all sequences are present.
7. Run the script - this will convert the sequences into a string, and then run a subprocess to perform the alignment. The displayed output following this will show the head of each aligned sequence, ready for export.
8. The script will then display the length of each aligned sequence. Check will all be the same as the others for a successful alignment. 

## Testing of the script
During production,the "Alignment of multiple sequences" script section was tested using the "Sequences_Fasta2.fa" file in this repository, with a segment of the "Glen Ample" sequence from this file used to test the "Simple tools for sequence investigation" section. This file can be downloaded from this repository for use alongside the script if you wish to test the script with alternative data prior to using your own.
