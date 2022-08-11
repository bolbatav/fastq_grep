# fastq_grep

A script to extract raw reads from FASTQ files by query sequence. You can search through multiple files for reads in forward, reverse-complevent, or both directions. The reads can be automatically converted to FASTA format in the out the output file.

Use -h/--help option for description.

# Changes in v.2:
1) -o option is deprecated. The script is now integrated into stdin/stdout, in case someone wants to pipe through it. Providing reads from file list still works.
2) The script now supports IUPAC ambiguity codes, though at a cost of greater processing time.
3) Semicolons and whitespaces are not automatically replaced with underscores, but the lines to are still there. Uncomment if necessary.
