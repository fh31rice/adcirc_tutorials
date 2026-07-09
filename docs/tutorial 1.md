
# Tutorial 1: Learning Resources for ADCIRC and SWAN

## Introduction

Learning ADCIRC can be challenging, especially without guidance 
from someone familiar with the model. Unlike many other software 
packages, video tutorials for ADCIRC are scarce — most resources 
exist as technical manuals, research papers, and GitHub repositories.

The goal of this tutorial is to provide a structured starting point 
for new users. Rather than covering every detail, this page gives 
you an overview of the best resources and where to find them.

## Resources

### What level of knowledge do I need?

If you are new to ADCIRC, here is what you should know beforehand:

ADCIRC is primarily run on **HPC (High Performance Computing)** 
systems, so a basic understanding of Linux commands and job 
schedulers like SLURM is helpful before you start.

### Getting ADCIRC Compiled

ADCIRC is open source and can be downloaded and compiled on 
your HPC system. However, compilation can be tricky for new 
users due to library dependencies. You have two options:

1. **Ask your HPC administrators** — most university HPC centers 
   can help install or compile ADCIRC for you
2. **Ask the ADCIRC community** — the ADCIRC Discord group has 
   experienced users who are happy to help newcomers

!!! tip
    If you are at a university, always check with your HPC 
    support team first — ADCIRC may already be installed.

### Do I need to have any software installed?

Yes, you should have a software called SMS. This software community version is free, but you need to have a licensed verson to do more complex tasks. Although it is not fully necessary to have any software to run ADCIRC, but sometimes mesh generation, viewing results etc. need the help of SMS software.

### Can I run ADCIRC inside SMS?

Yes, you can run ADCIRC inside SMS. But, this is mostly helpful to start with ADCIRC. Eventually you need to learn to run ADCIRC on HPC.

### Basically, what I need then to run ADCIRC?

1. ADCIRC compiled in HPC
2. SMS software