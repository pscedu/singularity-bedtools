![Status](https://github.com/pscedu/singularity-bedtools/actions/workflows/main.yml/badge.svg)
![Status](https://github.com/pscedu/singularity-bedtools/actions/workflows/pretty.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-bedtools)
![forks](https://img.shields.io/github/forks/pscedu/singularity-bedtools)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-bedtools)
![License](https://img.shields.io/github/license/pscedu/singularity-bedtools)

# singularity-bedtools
<img src="http://www.andrew.cmu.edu/user/icaoberg/post/singularity-bedtools-update/logo.png" width="10%">

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `bedtools` script

to `/opt/packages/bedtools/2.29.2`.

Copy the file `modulefile.lua` to `/opt/modulefiles/bedtools` as `2.29.2.lua`.

## Building the image using the recipe
### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2022 Pittsburgh Supercomputing Center. All Rights Reserved.

The [Biomedical Applications Group](https://www.psc.edu/biomedical-applications/) at the [Pittsburgh Supercomputing
Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/tigers/) at [Carnegie Mellon University](http://www.cmu.edu).

