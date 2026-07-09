### Description of ADCIRC Input Files

As I said earlier, ADCIRC basically runs on fortran script. So the ACDIRC files are named as fort.something. Say, fort.14 means it is a mesh file, fort.13 means it is a nodal attribute file. There are many input files in ADCIRC. All files are not necessary to run ADCIRC, it depends on your simulation purpose. ADCIRC wiki page and manual page I shared in some earlier section, already have all the description nicely written. I will not discuss in details about the input files here, but I will try to give an overall idea here about the files. **[ADCIRC on DesignSafe](https://www.designsafe-ci.org/user-guide/tools/simulation/adcirc/adcirc/)** — This page has a very good summary table of the ADCIRC input and output files, so to get an overall idea you can see this page as well.

### A basic overview:

1. fort.14: Mesh file - It is a mandatory file for ADCIRC simulation. This file is called the fort.14 file. This file basically contains the nodes, elements, lat, lon and elevation information of your mesh. I will discuss more about the generation of ADCIRC mesh, and how the file looks like in a seperate section.

2. fort.15: parameters file- This is a fortran file that contains all the parameters of ADCIRC. Say for example, the start of simulation, the time step, the advection term, the output format, the total runday, astronomical tide information, wind field forcing option and many more. I will discuss more about this file format in a seperate section.

3. fort.13 file: nodal attribute file - This file is a fort.13 file that contains nodal attributes. Say, manning's n, bottom friction, surface canopy etc. There are many parameters that you can use, but it is not mandatory to include all the roughness parameters here. Based on your study area and study objective you have to include these parameters. ADCIRC manual and wiki page has a good description of the parameters. I will discuss some important parameters that I have used in a seperate section.

4. fort.22 file - This fort.22 file is the hurricane file. There are different category of hurricane wind forcing that you can use. The options are called NWS. Say for example NWS 8 (symmetric hurricane Holland model from IBTrACS), NWS 20 (Asymmetric hurricane Holland model from IBTrACS), NWS 6 (gridded wind forcing coming from ERA5), NWS 12 (wind and pressure field in gridded format coming from OWI).  Every hurricane has all kind of wind forcing available. It depends on your work what wind forcing you will use, normally it is not guranteed which wind forcing will give you the best result. But there are some ways to understand that. Normally most people use NWS 20 and NWS 12 options. IBTrACS data is free to download, ERA5 is also free. But the OWI format data is not free.

There are also many other input parameters for ADCIRC. I will update this page time to time and include those.
