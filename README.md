# The Linux command line for scientific computing

Welcome to the class!

Below are the instructions on how to use this repository.  

Note: The videos are restricted to ICL students and staff.

## Setup

1. This class uses Jupyter Notebooks, decide if you want to use **Google Colab or Anaconda** on your own computer. Make sure that you **test your setup before the class so you can follow from the start**. Try the following on one or two notebooks 
   
    - **Method 1 - Google Colab in your browser and a command line application**:
        - Log into your Google account
        - Click on blue Colab links below
        - When open, save the notebooks in your drive with "File"->"Save a copy in Drive". This will let you execute commands in the code cells.
        - In notebooks 2 to 8, test the first code cell to download the practice data - this will have to be done for each notebook during the class, the data does not persist
        - **Windows users will also need a separate command line application**; choose one of the following.
            - [Git for Windows](https://gitforwindows.org) - relatively easy to install, no admin privileges required, installation [video](https://www.youtube.com/watch?v=339AEqk9c-8)
            - [Windows subsystem for Linux](https://www.windowscentral.com/install-windows-subsystem-linux-windows-10) - recommended but requires admin privileges 
        - [Download practice files](https://kmichali.github.io/SC-shell-novice/data/data-shell.zip) for use with a command line application. Place the data-shell directory on your desktop. Alternatively, you can use one of the following commands directly on the command line.
          - wget https://kmichali.github.io/SC-shell-novice/data/data-shell.zip; unzip data-shell.zip
          - curl https://kmichali.github.io/SC-shell-novice/data/data-shell.zip -o data-shell.zip; unzip data-shell.zip
        
        
    - **Method 2 - Anaconda on your own computer** (please note that **Windows users reported problems with using the course notebooks without enabling Windows subsystem for Linux** - see above):
        - Download this repository (that already includes the data) - instruction [video](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=59105d27-6102-483d-bf96-abd500e63b61)
        - Open a notebook in Anaconda using Jupyter Notebook - instruction [video](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=c12b4cfa-0875-456c-b691-abd500e6e2b3)
        - Jupyter Notebook contains in-built Terminal that will be used for command line practice
        - The practice files are already included in the repository
    
    
    
 
 ## Using the repository for learning (if you are attending a Graduate School class, we will do this together)
1. In the directory "notebooks", there are eight notebooks with video links.
    - **01 - Introduction and setup** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/01_introduction_and_setup.ipynb)
        - [video](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=abd2d252-6c29-4171-81b9-abd500efe82a)
    - **02 - Navigating files and directories** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/02_navigating_files_directories.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=4c78e22d-2b22-4464-b9fa-abd500fbd13d)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=f57ed93e-e0fe-4918-8182-abd501029064)
    - **03 - Working with files and directories**
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/03_working_files_directories.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=94a14b5d-dad4-49f9-9fd2-abd50118f1b2)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=450d3756-0838-473f-82e1-abd5011eb442)
    - **04 - Pipes and filters** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/04_pipes_filters.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0c667489-536e-40f0-9b1a-abd600d1e737)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=5de519db-bffd-46d5-a5fd-abd600d6017f)
    - **05 - For loops** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/05_for_loops.ipynb)
        - [video](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=cbaa59c0-8902-4047-8b8f-abd700ba3755)
    - **06 - Shell scripts**
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/06_shell_scripts.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=b61968f6-3bb1-4b41-898c-abd800bce5f0)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=7bca90d9-84fd-4849-a682-abd800c10869)
    - **07 - Finding things** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/07_finding_things.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=59575aed-9333-4f38-a2be-abd700c72bb1)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=e27ad876-7821-45fb-b957-abd700cb67c2)
    - **08 - Nelle's shell script** 
        - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kmichali/GS_comm_line/blob/master/notebooks/08_Nelles_script.ipynb)
        - [video 1](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=25c07517-6683-4f63-8d24-abd800cac743)
        - [video 2](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=1095126e-44f1-443d-9fc2-abd800ce6f3b)
        - [video 3](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=91ecd5c0-4454-4976-a3e2-abd800d37e0b)
        - [video 4](https://imperial.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=ed699b4f-95e2-4aa6-93bd-abd800d7d2ec)
1. Open the first notebook in Anaconda or in Colab.
1. Keep doing so until you have seen all eight notebooks.



Happy scripting!

Notebooks 1 to 7 are based on a snapshot of the [Unix Shell lesson](https://kmichali.github.io/SC-shell-novice/) from the [Software Carpentry](https://software-carpentry.org).


## Further study
- Local tutorials - systematic with lots of examples (ICL access only) - [Bash fundamentals](https://wiki.imperial.ac.uk/display/HPC/Command+line), [Bash scripting](https://wiki.imperial.ac.uk/display/HPC/Shell+scripting) 
- [Steve Parke's Bash tutorial](http://steve-parker.org/sh/sh.shtml) - with Linux administration spin
- [The Linux documentation project](http://tldp.org) - the most complete guide you can imagine
- [The Bash hackers wiki](http://wiki.bash-hackers.org/) - if you are looking for cool features
- [Short examples to play with](https://katerim@bitbucket.org/katerim/shellex.git)


<hr>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
