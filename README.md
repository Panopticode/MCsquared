# (MC)² - Multi-Core, Many-Core code for parallel thinking

(MC)², aka MCsquared, is a parallel software written in C using OpenMP
paradigm for memory management and CUDA to take advantage of the
GPU architectural model. This is to be intended as a stub for the final readme, with some fancy feature of the MarkDown syntax; the
authors of the project are:

  - Giacomo Marciani
  - Gabriele Santi
  - ...

The commissioner is still working on the official request for work, when done will be available on the [course site][pmc];
the professor, owner of this course, is [Massimo Bernaschi].
As reported on the site,

>Il corso ha forte orientamento applicativo ed ha lo scopo di presentare le principali 
>tecniche di programmazione di sistemi con elevato grado di parallelismo.
>Il corso prevede la realizzazione di un progetto e la presentazione e discussione di
>una breve relazione sul progetto stesso.

This type of applications do require indeed *deep abilities* to manage the technical
syntax of the C programming language, the knowledge of MPI standard interface and
OpenMP nevertheless.

### Version
0.0.1alpha

### Tech

We will use the following tools:

* [CUDA] - CUDA framework
* [CLion] - Ultimate Edition, with educational license; a professional IDE developed by JetBrains
* [Eclipse] - Community IDE supported by the Eclipse Working Group
* ...

We are still considering what license to use for the intellectual property, but we foresee to
make this code available and *open source*. The [public repository][github] is on GitHub, freely fork-able.

### Installation

On the project main directory:

```sh
$ git clone https://github.com/Panopticode/mc-squared.git
```
or, with SSH
```sh
$ git clone git@github.com:Panopticode/mc-squared.git
```

### Todos

 - pretty much everything still

License
----

The MIT License (see LICENSE)


**Copyright (c) 2016 Gabriele Santi, Giacomo Marciani**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [github]: <https://github.com/Panopticode/mc-squared>
   [massimo bernaschi]: <http://www.iac.rm.cnr.it/~massimo/Massimo_Bernaschi_home_page/Welcome.html>
   [pmc]: <http://www.iac.rm.cnr.it/~massimo/PMC.html>
   [CUDA]: <http://www.nvidia.com/object/cuda_home_new.html>
   [CLion]: <https://www.jetbrains.com/clion/>
   [Eclipse]: <http://www.eclipse.org/>

