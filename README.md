# detecting-powerlaw-distributions-in-scientific-citations
Summer 2024 project supervised by Research Scientist Junming Huang at the Paul and Marcia Wythes Center on Contemporary China, Princeton University

Part of the science of science.

### Princeton Research Computing
My main code for the project was through Princeton Research Computing's Adroit cluster. I set up the environment for the Jupyter notebook using my terminal.

#### Setting up the Environment
Note: My system during this project was Mac OS.
1. Go to terminal
2. Enter 'ssh [NETID]@adroitprinceton.edu'
3. Enter password
4. Submit Duo two-factor login
5. $ module load anaconda3/2024.2
6. $ conda create --name [NAME-ENV] ipykernel powerlaw -c conda-forge
7. $ exit
8. $ module load anaconda3/2024.2
9. $ conda activate [NAME-ENV]
10. $ pip install powerlaw
11. $ pip install pandas
12. $ pip install matplotlib
13. $ pip install matplotlib.pyplot
14. $ pip install scipy
15. exit

##### Descriptions of packages
- powerlaw: Graph fit of empirical data pdf to the power law distribution pdf.
- pandas: Handle provided data.
- matplotlib: Graph change in gamma. Graph the probability density function of citation frequency over the years using a colormap.
- scipy: Use linear regression to calculate change in gamma over the years.

#### Jupyter on Adroit
For Adroit, fill out the online registration form [https://forms.rc.princeton.edu/registration/](url). You will be notified once your account is approved. A sponsor is not needed for Adroit.
After receiving the email confirming "Account created on Adroit as requested.":
1. Head to https://myadroit.princeton.edu/pun/sys/dashboard/
2. Click on My Interactive Sessions
3. Under Interactive Apps, click on Jupyter, which will launch a Jupyter server using Python on the Adroit cluster.
4. Fill out any necessary informtion to launch a session (I used 10 cores, 128 GBs, and 2024.2 as my Anaconda version)
5. Click Launch
6. Create a new notebook
7. Select the kernel as the one set up in the terminal.


### Power-law
To familiarize myself with power-law distribution, I read chapters 4-7 of http://networksciencebook.com/ as recommended by Research Scientist Junming Huang.
