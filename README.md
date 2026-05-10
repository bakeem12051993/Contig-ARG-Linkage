# Contig-ARG-Linkage
Reproducible Snakemake pipeline that links antibiotic resistance genes to bacterial hosts in metagenomic data. For each sample, it assembles reads (MEGAHIT), detects ARGs (BLASTn vs MEGARes), classifies contigs (Kraken2), and joins by contig ID. Pinned envs, checksummed databases, container builds, and CI-tested on synthetic data.
