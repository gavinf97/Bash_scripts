# Bash_scripts
## Overall Repository Decscription
Repository contains a slection of Bash shell scripts used during my MSc project for data management, merging and QC. Pertinent to AntiSMASH GenBank and Biosynthetic MetaSpades outputs. 

## Scripts useful in conjunction with; 
-AntiSMASH https://antismash.secondarymetabolites.org/#!/start https://doi.org/10.1093/nar/gkab335  
-Biosynthteic MetaSpades https://github.com/ablab/spades https://dx.doi.org/10.1101%2Fgr.213959.116


## Bash Script Descriptions
### 1. antismash_merger.sh
Merges GenBank files in respective AntiSMASH output folder into a single file.

### 2. antismash_multirun.sh
Runs AntiSMASH analysis tool on Biosynthetic MetaSpades processed fasta files; will run on each 'genecluster' fasta iteratively.

### 3. fasta_merge.sh
Merges Biosynthetic MetaSpades output fasta files to one file form their subdirectories and also pases out fasta read length data.

### 4. filesample_parse.sh
Compiles filename accessions together into one txt file from their base file name if in directory with several result folders and shows sample names used.

### 5. gbk_counter.sh
Useful during GenBank file management; counts number of GenBank files in curent directory.

### 6. gbk_read_counter.sh
Collects GenBank count data outputs from AntiSMASH into one file, breaks by common parsable marker and includes sample origin for use in analysis.

### 7. merge_scaffolds.sh
Merge scaffold fasta outputs from Biosynthetic MetaSpades into one unified file. Can be used further on fasta files with tweaking.

### 8. metaspades_fasta_merge.sh
Collects fastas together into one file, breaks by common parsable marker and includes fasta origin filename

### 9. remove_empty.sh
Removes empty files in all subdirectories; clears away and identifies failed ANtiSMASH/ Biosynthetic MetaSpades analyses 
