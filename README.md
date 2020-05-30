# diffexpr # 
[![Build Status](https://travis-ci.org/wckdouglas/diffexpr.svg?branch=master)](https://travis-ci.org/wckdouglas/diffexpr)

A python package using ```rpy2``` to port [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html) into python.

## INSTALL ##
Dependencies are ```pandas``` (python), ```rpy2``` (python), and ```DESeq2``` (R)
Best way to build dependencies should be via conda. 

```
conda config --add channels r
conda config --add channels bioconda
conda config --add channels auto
conda config --add channels conda-forge

conda install pandas rpy2
Rscript setup.R #to install DESeq2 correctly 
```

## Example ##
An example of running DESeq2 in *python* using ```diffexp``` package is provided [here](https://github.com/wckdouglas/diffexp/blob/master/example/deseq_example.ipynb).
