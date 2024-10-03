# Analysis of Tanpura Tunings

This project explores the tuning systems of the Tanpura, a classical Indian instrument, using signal processing techniques in Python. The objective is to identify the tuning of a 4-stringed Tanpura and the key of the tuning through analysis of recorded audio samples.

## Key Features

- Analyzes Tanpura tunings using spectrograms, chromagrams, and energy distributions.
- Applies techniques like Discrete Fourier Transform (DFT) and Short-Time Fourier Transform (STFT) to extract audio features.
- Identifies tuning keys using band-pass filtering, median filtering, and global thresholding.

For detailed understanding, check out the report for this project and feel free to contact.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/groverv358/Tanpura_tuning_project.git
   cd tanpura-tuning-analysis
2. InstalL FMP environment:
   ```bash
   Download files from https://www.audiolabs-erlangen.de/resources/MIR/FMP/FMP_1.2.6.zip
   Create a conda environment:
   conda env create -f environment.yml

## Dataset Description

There are three resources of data for the project. These are in the "Data" folder in this repository :-
1. <b>Mobile Tanpura Applications</b> : There are recordings from applications such as TanpuraDroid, Bandish and Singtico. There are folders with the same name. These folders have sub-folders: SaPa, SaMa and SaNi. These names corresponds to the names of the tunings of four stringed Tanpuras. The above mentioned folders contains audio recordings, each of 15 seconds length for all the keys from A to G# for all the tuning systems from each Tanpura application. <p> SaPa is for Pa SA SA Sa, SaMa is for Ma SA SA Sa and SaNi is for Ni SA SA Sa where the each notes denotes the pitch to which the first, second, third and fourth strings are tuned. Sa, Pa, Ma and Ni are of the lower octave and SA is of the middle octave. </p> 
2. <b>Youtube Recordings</b> : The folder named "Youtube" contains random  Tanpura recordings of each tuning system for some keys to test tout the method proposed for finding the tuning of Tanpura. These audio clips are of 55 seconds length.
3. <b>OSF Database</b> : The folder named "OSF Database" contains the small audio clips of Tanpura from the live performance for various Ragas. These clips have been cut out of the original live performance audios. So each each of them have different durations from each each other. But each clip have at;east one cycle of string plucking.

For detailed explaination of the procedure for finding the tuning of the Tanpura, read "Analysis_of_Tanpura_Tunings.pdf".
