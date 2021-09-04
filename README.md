# Bash_scripts
## Overall Repository Decscription
Repository contains a slection of Bash shell scripts used during my MSc project for data management, merging and QC. Pertinent to AntiSMASH GenBank and Biosynthetic MetaSpades outputs. Scripts useful in conjunction with AntiSMASH and Biosynthteic MetaSpades tools and their output data.

## Bash Script Descriptions
### 1. antismash_merger.sh
Merges GenBank files in respective AntiSMASH output folder into a single file.

### 2. antismash_multirun.sh
Runs AntiSMASH analysis tool on Biosynthetic MetaSpades processed fasta files; will run on each 'genecluster' fasta iteratively

### 3. fasta_merge.sh
Merges Biosynthetic MetaSpades output fasta files to one file form their subdirectories and also pases out fasta read length data

### 4. filesample_parse.sh
Compiles filename accessions together into one txt file from their base file name if in directory with several result folders and shows sample names used.
