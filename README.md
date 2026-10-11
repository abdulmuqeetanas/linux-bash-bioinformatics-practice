# Linux/Bash for Bioinformatics: DNA Sequence Analysis

## Project Overview

This beginner bioinformatics project demonstrates how Linux and Bash commands can be used to manage biological sequence files, extract DNA sequences, calculate GC content, and generate analysis reports.

The project was completed using Google Colab and a Linux command-line environment.

## Project Objectives

- Practice basic Linux commands and directory navigation.
- Create and organize DNA sequence files in FASTA format.
- Extract a specific DNA sequence using command-line tools.
- Calculate DNA sequence length and GC content.
- Generate and save a text-based analysis report.

## Tools and Technologies

- Linux / Bash
- Google Colab
- FASTA file format
- `grep`, `cat`, `ls`, `pwd`, `mkdir`, `find`, `wc`, and `awk`

## Files

| File | Description |
|---|---|
| `Linux_Bash_Bioinformatics_Practice.ipynb` | Notebook containing Linux/Bash exercises and sequence analysis |
| `genes.fasta` | Example DNA sequences used for practice |
| `TP53.fasta` | Extracted example sequence labeled TP53 |
| `TP53_GC_analysis.txt` | Saved DNA sequence analysis results |

## Results

The example TP53-labeled DNA sequence produced the following results:

| Measurement | Result |
|---|---|
| Sequence length | 30 nucleotides |
| G + C count | 17 |
| GC content | 56.67% |

GC content was calculated using:

GC Content (%) = ((G + C) / Total Nucleotides) × 100

## Skills Demonstrated

This project provided hands-on practice with Linux directory navigation, file management, text processing, FASTA sequence handling, and basic Bash-based DNA sequence analysis.

## Limitations

The DNA sequences used in this project are illustrative practice sequences rather than experimentally verified gene sequences. The analysis demonstrates basic computational methods and does not establish biological or clinical conclusions.
