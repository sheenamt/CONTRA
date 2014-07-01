CONTRA
======

Fork of the CONTRA v2.0.4 package found at http://sourceforge.net/projects/contra-cnv/.


This fork was created to address the specific issue of empty vcf and fastaOut files.
This error was caused by the convert_targeted_regions.py script inserting "chr" into the bed file, which then did not match the fasta file.

