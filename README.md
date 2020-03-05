# conda_install
## install 2019.10 anaconda 3 under ~/conda3
## logout and in to start conda
## conda create -n r36
## conda activate r36
## conda install -y r-base tmux r-seurat bioconductor-maftools vim
## https://github.com/junegunn/vim-plug:
### curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
## R
    conda install r-tidyverse r-caret r-stringi \
	bioconductor-deseq2 r-bit64
   
## python 2
    conda create  --name python2 \
	python=2.7 pip numpy cython scipy scikit-learn seaborn \
	matplotlib xopen pysam pybedtools \
	rpy2 bioconductor-deseq2 bioconductor-dexseq \
	jupyter ipykernel ipython 

# bioinformatics
    conda install -c bioconda hisat2 seqtk \
	    bowtie2=2.2.5 atropos bedtools bowtie \
	    bamtools samtools bwa seqkit \
	    picard fastqc datamash csvtk \
	    parallel bwameth pileometh \
	    viennarna cutadapt blast \
	    ucsc-wigtobigwig ucsc-bedtogenepred \
	    ucsc-gtftogenepred ucsc-genepredtobed \
	    ucsc-bigwigtobedgraph ucsc-bigwigtowig \
	    ucsc-bedgraphtobigwig 
