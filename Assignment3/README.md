# Assignment #3 GFF feature files and visualization

This is our scripts and files from Assignement 3.
**Authors:** David García Valcarce and Jimena Martín Reina.

## Database used in the exercise 1 from the assignment

We have used the dbfetch API from the European Bioinformatics Institute (EMBL-EBI) to access the Ensembl Genomes database through the URL http://www.ebi.ac.uk/Tools/dbfetch/dbfetch?db=ensemblgenomesgene&format=embl. 
This specific URL is designed to retrieve genomic information, including sequences, from the Ensembl Genomes database.

## Scripts

In this repository you will find:
- A main script called "main.rb".
- Two secondary scripts called "gene.rb" and "methods.rb".

## Files

This scripts need just one input file, which has the genes' IDs:
- ArabidopsisSubNetwork_GeneList.txt

Three output files are generated by the scripts:
- target_matches_4a.gff
- target_matches_5.gff
- no_matches_report.txt