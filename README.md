# MD_TM_protein
Group of scripts with could help run and analyse long trajectories of MD simulations protein-membrane systems _**only by NAMD**_ prepared by CHARMM GUI

CHARMM GUI output should be placed into _**MD_TM_protein/MD**_ folder
Scripts are counting protein parameters such as SASA, Ramachandran, protein energy and could interact amino acids of protein with water. 
They also can trace the network of interprotein interactions. Scripts also could analyse could ligands interact with ligands. 


# Dependencise

## Programs

1. NAMD (NAMD could be downliaded from https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=NAMD you should copy namd multicore into _**MD_TM_protein/programm/**_ folder)
2. VMD (VMD could be downliaded https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD)
3. R (sudo apt-get update sudo apt-get install r-base r-base-dev or read https://cran.r-project.org/bin/linux/debian/)
4. dssp Debian and Ubuntu (sudo apt install dssp)
5. ring2 (could be downloaded form http://old.protein.bio.unipd.it/download/)
6. Autodock (Autodock vina into _*stabilisation_complex-receptor-ligand/programs/autodock_vina_1_1_2_linux_x86*_ from http://vina.scripps.edu/download.html)
7. MGLTools (MGLTools into _*stabilisation_complex-receptor-ligand/programs/MGLTools-1.5.7*_ from https://ccsb.scripps.edu/mgltools/downloads/, and you shold chouse this wersion of the ptogram _*mgltools_Linux-x86_64_1.5.7_Install (Linux 64 GUI installer 109Mb)*_ or rename folder atherthords to _*stabilisation_complex-receptor-ligand/programs/MGLTools-1.5.7*_)

## R packages

1. bio3d install.packages("bio3d")
2. cowlpot install.packages("cowlpot")
3. ggplot2 install.packages("ggplot2")
4. dplyr install.packages("dplyr")
5. httr install.packages("httr")
