![Status](https://github.com/pscedu/singularity-bedtools/actions/workflows/main.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-bedtools)
![forks](https://img.shields.io/github/forks/pscedu/singularity-bedtools)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-bedtools)
![License](https://img.shields.io/github/license/pscedu/singularity-bedtools)

![Logo](images/logo.png)

Collectively, the [bedtools](https://bedtools.readthedocs.io/en/latest/) utilities are a swiss-army knife of tools for a wide-range of genomics analysis tasks. The most widely-used tools enable genome arithmetic: that is, set theory on the genome. For example, bedtools allows one to intersect, merge, count, complement, and shuffle genomic intervals from multiple files in widely-used genomic file formats such as BAM, BED, GFF/GTF, VCF. While each individual tool is designed to do a relatively simple task (e.g., intersect two interval files), quite sophisticated analyses can be conducted by combining multiple bedtools operations on the UNIX command line.

## Pre-requisites

* [Singularity v3.5.+](https://sylabs.io/docs/).

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `bamtools` script

to `/opt/packages/bedtools/2.29.2`.

Copy the file `modulefile.lua` to `/opt/modulefiles/bedtools` as `2.29.2`.

## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image locally.

```
bash ./build.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2021 Pittsburgh Supercomputing Center. All Rights Reserved.

The [Biomedical Applications Group](https://www.psc.edu/biomedical-applications/) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).

