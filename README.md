# common-conda-enviroments
some daily used conda environments


# set repository mirrors

  conda config --add channels defaults
  conda config --add channels bioconda
  conda config --add channels conda-forge

*make sure the **conda-forge** channel has the highest priority (the last one to be added), followed by **bioconda** channel.*

In China, you can use the following channles instead:

  conda config --add channels http://mirrors.ustc.edu.cn/anaconda/cloud/bioconda/
  conda config --add channels http://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/

  conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/bioconda/
  conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge/


# jupyterlab

  conda create -n jupyterlab jupyterlab biopython plotnine=0.4.0 seaborn ggplot rpy2 R xlrd ete3 easysvg beautifulsoup4 lxml html5lib cython

# ngsutils
  conda create -n ngsutils ngsutils

# python3.6
  conda create -n python3.6 python=3.6

# python2.7
  conda create -n python2.7 python=2.7

# R
  conda create -n R3.4 R=3.4

# aligner
  conda create -n aligner blast=2.7.1 MAFFT=7.313 clustalw tophat
    bwa=0.7.8
    
# htslib
  conda create -n htslib  Htslib=1.7 samtools=1.7 bcftools=1.7 bamtools=2.4.1 Picard=2.14

# seqtools
  conda create -n seqtools skewer=0.2.2 vsearch=2.7.0 EMBOSS seqkit=0.8.0 biokit=0.4.2  fastx_toolkit sra-tools=2.8.2

# phylogenetic
  conda create -n phylogenetic paml beast2 phylip=3.696 iqtree=1.5.5 circos=0.69.6 raxml=8.2.10

# assembler
  conda create -n assembler KmerGenie cap3 soapdenovo2 soapaligner soapcoverage  soapdenovo2-errorcorrection soapdenovo2-gapcloser soapdenovo2-prepare Cufflinks obitools

# genetools
  conda create -n genetools busco=3.0.2 HMMer=3.1b2 exonerate=2.4.0  INFERNAL=1.1.2 tRNAscan-se=2.0 RAxML=8.2.10 ViennaRNA=2.4.4

# gatk4
conda create -n gatk4  gatk4

# galaxy-lib
  conda create -n galaxy-lib galaxy-lib=18.5.5

# maker
  conda create -n maker maker
  
# mitozEnv
  conda create  -n mitozEnv libgd=2.2.4 python=3.6.0 biopython=1.69 ete3=3.0.0b35 perl-list-moreutils perl-params-validate perl-clone circos=0.69 perl-bioperl blast=2.2.31  hmmer=3.1b2  bwa=0.7.12 samtools=1.3.1 infernal=1.1.1 tbl2asn openjdk

