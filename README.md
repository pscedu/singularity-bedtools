![Status](https://github.com/pscedu/singularity-bedtools/actions/workflows/main.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-bedtools)
![forks](https://img.shields.io/github/forks/pscedu/singularity-bedtools)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-bedtools)
![License](https://img.shields.io/github/license/pscedu/singularity-bedtools)


![Logo](images/logo.png)



## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

You will need to edit the script above to match your account on [SyLabs.io](https://sylabs.io/).

### Pulling from the repository
If you have the client installed and cannot build the image locally nor remotely, simply run

```
singularity pull --arch amd64 library://icaoberg/default/bedtools:v2.29.2
```

## Disclaimer

I am nothing but a humble programmer creating the container for this wonderful app. [bedtools](https://bedtools.readthedocs.io/en/latest/) is developed in the [Quinlan laboratory](http://quinlanlab.org/) at the [University of Utah](https://www.utah.edu/) and benefits from fantastic contributions made by scientists worldwide.

---
[![CBD](http://www.cbd.cmu.edu/wp-content/uploads/2017/07/wordpress-default.png)](http://www.cbd.cmu.edu)

Copyleft © 2019-2020 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)
