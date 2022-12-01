Last update: 1/12/2022

# Tutorial on DER Hosting Capacity - Part 2: Time-Series Analysis of Three-Phase Unbalanced LV Networks

## Tutorial on DER Hosting Capacity

This Tutorial on Distributed Energy Resource (DER) Hosting Capacity will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics) on realistic three-phase unbalanced distribution networks. Throuhought this tutorial we will be using OpenDSS (https://sourceforge.net/projects/electricdss/) - an open source distribution network analysis tool developed by the Electric Power Research Instutite (EPRI, https://www.epri.com/), USA. Thanks to our colleagues and friends at EPRI for this important contribution to the world!

This Tutorial is designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. It requires coding knowledge - of course!. But not too advanced. If you are a decent coder, you will manage ;-)

## Part 2: Time-Series Analysis of Three-Phase Unbalanced LV Networks

Part 2 is about carrying out different time-series analyses of low voltage (LV) networks.

After doing this tutorial, you are expected to:
- Gain more understanding of the characteristics and behaviour of residential, three-phase LV distribution networks.
- Understand the simulation process necessary to study different solar PV penetration levels and assess the corresponding voltage rise and/or asset congestion issues.
- Understand how to determine the solar PV hosting capacity of LV networks.

### Pre-Requisites for Part 2
- You should have completed [Part 1](https://github.com/Team-Nando-Training/Tutorial-DERHostingCapacity-1-dss_python) and, of course, be familiar with [OpenDSS and the modelling of distribution networks and DERs](https://sites.google.com/view/luisfochoa/research-tools/opendss-training-material).


## Run Part 2
### Files
- Download the source code (the .zip file will do) from the [releases section](https://github.com/Team-Nando-Training/Tutorial-DERHostingCapacity-2-TimeSeries_LV/releases) or clone the entire repository to your local drive using GitHub Desktop. Unzip the file. It is important to place all the unzipped files in the same folder.
- Although there are multiple files, the following are the **key files** that will be uploaded to Jupyter Notebook.  
   - File 1. `Tutorial-DERHC-2.ipynb` - the main Jupyter file  
   - File 2. `LVcircuit-topology.png` - the graph of the test LV circuit  
   - Files 3 to 8. `LVcircuit-master.txt`, `LVcircuit-transformers.txt`, `LVcircuit-linecodes.txt`, `LVcircuit-lines.txt`, `LVcircuit-serviceLines.txt`, `LVcircuit-loads.txt` - the OpenDSS commands that describe the test LV circuit  
   - File 9. `Residential load data 30-min resolution.npy` - the 30-min resolution dataset of house load  
   - File 10. `Residential PV data 30-min resolution.npy` - the 30-min resolution dataset of PV output  
- Run Jupyter Notebook (it will open a tab on your browser). Jupyter Notebook uses a localhost address to store and manage files. You can either upload files on its webpage or access your local folder for direct copy and paste. You can also change the default address of Jupyter Notebook in its config file.
- Upload the **key files** (create a folder to be more organised).
- Here is a way for the beginner to run the .ipynb file
  - Open **Anaconda Prompt** and type "jupyter notebook --notebook-dir=`your address stored this project`". For example, jupyter notebook --notebook-dir=C:\OpenDSS
  - Jupyter notebook will be opened in your browse. Click on `Tutorial-DERHC-2.ipynb`and you can play now.

### Execute the `Tutorial-DERHC-2.ipynb` file
- The tutorial will appear on a new tab.
- Now you can explore the tutorial by running each cell accordingly (click on the **play button** on the left). Just bear in mind that the variable values are stored, so you need to clear all the outputs manually every time you want to intiate the whole program. Go to the Jupyter Notebook menu on top, select **Kernel** and then **Restart & Clear Output**.

## Credits
### This Repo and Adaptations to the Original Python Code
Angela Simonovska (asimonovska@student.unimelb.edu.au)  
Yushan Hou (yushou@student.unimelb.edu.au)  
Jing Zhu (jing.maviszhu@student.unimelb.edu.au)  
Muhammad Zulqarnain Zeb (mzeb@student.unimelb.edu.au)  
Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)

### Original Python Code
Andreas Procopiou (andreasprocopiou@ieee.org)

## Acknowledgement

The content of this repository has been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).

* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members

## Licenses

Since this repository uses dss_python which is based on OpenDSS, both licenses have been included. This repository uses the BSD 3-Clause "New" or "Revised" license. Check all corresponding files (`LICENSE-OpenDSS`, `LICENSE-dss_python`, `LICENSE`).
