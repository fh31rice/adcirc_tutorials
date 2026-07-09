
# General Questions 

## Introduction

ADCIRC is basically used for storm surge modeling. In general, if I have to describe easily, say a hurricane is approaching, so we can use that hurricane information (i.e., wind field, pressure, timing and position of hurricane etc.) to see what is the storm surge or water level along the coastline. ADCIRC just works like other hydrodynamic model. It requires mesh, parameters, boundary condition, hurricane information, nodal attributes (i.e., roughness). But, learning ADCIRC initially can be challenging. Unlike many other software 
packages, video tutorials for ADCIRC are scarce — most resources 
exist as technical manuals, research papers, and GitHub repositories.

The goal of this page is to provide a structured starting point 
for new users. Rather than covering every detail, this page gives 
you an overview of the best resources and where to find them. I will try to give some guidelines based on my experience of using ADCIRC.


### Q1. What level of knowledge do I need?

If you are new to ADCIRC, here is what you should know beforehand:

ADCIRC is free to download and primarily run on **HPC (High Performance Computing)** 
systems, so a basic understanding of Linux commands and job 
schedulers like SLURM is helpful before you start. Also, ADCIRC input and output files are written on fortran scripts. So, a basic undersanding of fortran will help you. It is not mandatory to have a very good idea about fortran, you will mostly need to understand the parameters how they are written in ADCIRC. I would say, you will eventually be familiar with time to time while working with these scripts.

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

### Q2. Do I need to have any software installed?

Yes, you should have  **[SMS Software](https://aquaveo.com/downloads-sms)** — 
  surface water modeling. This software community version is free, but you need to have a licensed version to do more complex tasks. Although it is not fully necessary to have any software to run ADCIRC, but sometimes mesh generation, viewing results etc., you will need to use SMS software.

### Q3. Can I run ADCIRC inside SMS?

Yes, you can run ADCIRC inside SMS. But, this is mostly helpful to start with ADCIRC. Eventually you need to learn to run ADCIRC on HPC.

### Q4. Where to get training informations on ADCIRC?

ADCIRC training sessions are held **yearly in the USA** and are 
one of the best ways to get hands-on experience with the model.

- **[ADCIRC LinkedIn Page](https://www.linkedin.com/showcase/adcirc-week/posts/?feedView=all)** 
  — announcements for upcoming training sessions and workshops
- **Dr. Jason Fleming** (jason.fleming@adcirc.live) — can provide 
  more information about training opportunities

### Q5. How much should I know to use HPC?

You should have some ideas about basic commands, say like, how to open account and access HPC, how to change directory, add directory, how to upload and download files to HPC, how to submit job in HPC etc. Normally every educational institute have some resources to give training on HPC to the new users, so try to find those from your university and attend.

### Q6. So, basically, what I need then to run ADCIRC?

1. ADCIRC compiled in HPC
2. SMS software

