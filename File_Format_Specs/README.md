# File Format Specifications

Genomics data comes in all sorts of different shapes and sizes and can be tricky to work with! Here's some information on some of the different file formats we work with and the tools required to process said formats. 

* SAM files (BAM files are the binary equivalent) - we usually use the tool SAMtools to manipulate them - https://samtools.github.io/hts-specs/SAMv1.pdf

* VCF files (BCF files are the binary equivalent) - we usually use VCFtools or BCFtools - https://samtools.github.io/hts-specs/VCFv4.2.pdf

* BED files - BEDtools for file manipulation - http://genome.cse.ucsc.edu/FAQ/FAQformat.html#format1

* FASTQ - there's not so much of a formal specification, nor a widely used toolkit, but here's a paper on em - https://academic.oup.com/nar/article/38/6/1767/3112533

