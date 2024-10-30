# Tutorial on DER Hosting Capacity - Part 2: Time-Series Analysis and PV Hosting Capacity of LV Networks

## Tutorial on DER Hosting Capacity

This multi-part Tutorial on Distributed Energy Resource (DER) Hosting Capacity will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics ☀️🏡) on realistic three-phase unbalanced distribution networks.

This Tutorial is designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. It requires some knowledge of coding (of course! 🤓) but not too advanced. If you are a decent coder, you will manage 😉.

## Part 2: Time-Series Analysis and PV Hosting Capacity of LV Networks

The objectives of this tutorial are:
1. To familiarise with the process by which power engineers can carry out **time-series analyses and determine the PV Hosting Capacity of a given LV distribution network**. To achieve this, you will run multiple time-series power flows with different PV penetratration levels and assess when the resulting effects go beyond the capabilities of a given LV network.

2. To continue familiarising with **advanced tools** useful to run distribution network studies involving DERs. You will continue using [OpenDSS](https://www.epri.com/pages/sa/opendss) via the [dss_python](https://github.com/dss-extensions/dss_python) module. And, to guide you, all will be done using a notebook on [Jupyter Notebook](https://jupyter.org/).

## Run Part 2
To make the most of Part 2, you should have completed [Part 1](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-1-AdvancedToolsLV). and, of course, be familiar with [OpenDSS for Beginners and the modelling of distribution networks and DERs](https://sites.google.com/view/luisfochoa/research-tools).  

Choose one of the options below to run Part 2.

### Cloud Option ☁️: Google Colab
Just click on the badge <a target="_blank" href="https://colab.research.google.com/github/Team-Nando/Tutorial-DERHostingCapacity-2-TimeSeries_LV/blob/main/Tutorial-DERHC-2.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg"/></a>. You don't need to install anything 🤓💪.

### Local Option 💻: Jupyter Notebook
Make sure you have installed Anaconda, the dss_python module, etc. as specified in [Part 0](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-0-dss_python). Otherwise, you will not be able to go through the tutorial. To guarantee that you have all the necessary packages you can also run the  **`requirements.txt`** file using  **`pip install -r requirements.txt`** on the Anaconda prompt.

1. Download all the files using the green **`<> Code`** button at the top right.
   - You will get a ZIP file with a folder that contains all the files.
   - Unzip the file an place the folder somewhere in your computer/laptop.
2. To open the Jupyter notebook file (extension **`ipynb`**) you need to:
   - Open Anaconda Navigator
   - Click on Launch Jupyter notebook (it will open in your browser)
   - Upload the unzipped folder (with all the corresponding files) to Jupyter Notebook (the location is up to you)
   - Go inside the folder and open the **`ipynb`** file
   - Now you can explore the tutorial by running each cell accordingly (click on the **play button** in the menu). Just bear in mind that the variable values are stored, so you need to clear all the outputs manually every time you want to intiate the whole program. Go to the Jupyter Notebook menu on top, select **Kernel** and then **Restart & Clear Output**.

All the tutorial instructions will be in the **`ipynb`** file.
<br>
<br>
Enjoy! 🤓

## Credits
### This Repo and Adaptations to the Original Python Code
Angela Simonovska (asimonovska@student.unimelb.edu.au)  
Yushan Hou (yushou@student.unimelb.edu.au)  
Jing Zhu (jing.maviszhu@student.unimelb.edu.au)  
Muhammad Zulqarnain Zeb (mzeb@student.unimelb.edu.au)  
Orlando Pereira Guzman (opereiraguzm@student.unimelb.edu.au)  
Fahmi Angkasa (angkasaf@student.unimelb.edu.au) <br>
Andres Avila Rojas (aavilarojas@student.unimelb.edu.au)  
Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)

### Original Python Code
Andreas Procopiou (andreasprocopiou@ieee.org)

## Acknowledgement

The content of this repository has been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).

* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members

## Licenses

Since this repository uses dss_python which is based on OpenDSS, both licenses have been included. This repository uses the BSD 3-Clause "New" or "Revised" license. Check all corresponding files (`LICENSE-OpenDSS`, `LICENSE-dss_python`, `LICENSE`).
