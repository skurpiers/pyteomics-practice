# pyteomics-practice
This project was completed as preparation for my summer 2020 data engineering internship at Genentech. Completing this jupyter notebook was a way of practicing with python and pyteomics, and introducing myself to mass-spectrometry analysis.

The notebook uses python & pyteomics to: <br>
1.find and open/read a thermo-fisher .raw 'peptide map' data file <br>
2. read in a fasta file with one protein sequence <br>
3. 'digest' the sequence with trypsin <br>
4. calculate the masses of tryptic peptides <br>
5. calculate the mass-to-charge of all tryptic peptides assuming that they are ionized with +1 to +3 charge states <br>
6. "Search" the peptide map data for each ion <br>
7. answer 'how many of the amino acids (% of total) in your protein did you identify?' <br>
8. answer 'does this % change if you use a different file?' <br>

Pyteomics Example 2 from the docs is also mocked at the end of the notebook.

Fasta files come from UniProt and Undepleted Human Serum Mass Spec raw data is from UCSD MassIVE, acquired on Orbitrap Fusion Lumos Mass Spectrometer. - https://www-sciencedirect-com.proxy.lib.umich.edu/science/article/pii/S2352340920305515#ec-research-data
