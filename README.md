# Nano_variant


The sript here is to process nanopore generated raw reads for HIV env variant identification. The pipeline incorporates bioinformatics tools to perform basecalling, HIV env gene determination, quality plot, consensus transcript generation, error correction, chimera removal, HIV env variant identification, and env sequence genotyping. The code was tested comphrehensively under Python 3.6.10.

To install required python packages are:

pip install biopython pandas numpy subprocess argparse

The required external softwares are:

conda install -c bioconda nanoplot usearch cutadapt blast seqtk HMMER medaka racon minimap2 samtools

dorado: https://github.com/nanoporetech/dorado

vsearch (optional): conda install -c bioconda vsearch





