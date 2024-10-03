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

There are three types od data in the "Data" folder :-
1. Mobile Tanpura Applications : There are recordings from applications such as TanpuraDroid, Bandish and Singtico. There are folders with the same name. These folders have sub-folders: SaPa, SaMa and SaNi. These names corresponds to the names of the tunings of four stringed Tanpuras. <p> SaPa is for Pa SA SA Sa, SaMa is for Ma SA SA Sa and SaNi is for Ni SA SA Sa where the each notes denotes the pitch to which the first, second, third and fourth strings are tuned. Sa, Pa, Ma and Ni are of the lower octave and SA is of the middle octave. </p> <p>The above mentioned folders contains audio recordings, each of 15 seconds length for all the keys from A to G# for all the tuning systems from each Tanpura application.</p>
    
2. Youtube Recordings : 
3. OSF Database
