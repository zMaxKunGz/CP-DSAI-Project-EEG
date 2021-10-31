# Work Log
<b> [Week 3 : 25-29 Oct 2021]</b> <br>
Right now we can download and import the dataset into our project. In this week we focus on how to preprocessing dataset for training. <br> <br>
<b>Pasit:</b> <br>
<b>Saratoon:</b>try to preprocess the data by following the example and try to understand the code as well as find more info about each preprocessing step. <br>
<b>Nopphawan:</b> <br>
<b>Nuttun:</b> <br>
<br>

<b> [Week 2 : 18-22 Oct 2021]</b> <br>
In this week we discuss about the dataset to choose. For this project we use Brain Invaders calibration-less P300-based BCI with modulation of flash duration Dataset (bi2015a) as our dataset for testing.<br> 
<a>https://zenodo.org/record/3266930#.YW_noxrP2Uk</a> <br>
After we have selected the dataset, we try to understand the experiment behind the dataset and try read all document that the dataset owner provide.<br>
We also need to setup our environment for this testing for each person in our group. Also, try to load the dataset and import to python code.<br>
In the next week we will focus on preprocessing the dataset for training and find some paper about appropriate model for classification.<br> <br>
<b>Pasit:</b> Try to load data into project by using the library that project owner provide. Reading the library code to understand process that the project owner use to process and import data. Read about mne library. Testing some code.<br>
<b>Saratoon:</b>read BCI papers (80%),find and reads other papers of how to preprocess the EEG data and try to understand them.try some of the preprocessing method. <br>
<b>Nopphawan:</b> Set up new environment and install all neccesary packages, Read the document about MNE package. Try to play with MNE package.<br>
<b>Nuttun:</b>Read about BCI paper in classroom (80%), try to understand the process releted "Brain Invaders" and also set up environment for coding. Try to understand 'mne' library<br>
<br>

<b> [Week 1 : 11-15 Oct 2021] </b> <br> 
In this week we mostly disscuss about the datasets we are going to work with and try to understand basic BCI. <br> 
The categery our group choose to work with is Event Related Potentials datasets. Our group choose to study more about the dataset target vs non target. <br>
Focus on the BCI experiment about playing Brain Invaders games. <br> <br>

<b>Pasit:</b> Read About BCI (40%), understanding sustained attention driving dataset paper and about the experiment setup,<br> 
<b>Saratoon:</b> Read About BCI papers (50%), Read the overview of Face houses discrimination Paper and their dataset.<br> 
<b>Nopphawan:</b> Read a BCIs paper (40%), try to understand overview of BCIs and find and read some interesting papers: Brain Invaders, and ERP <br> 
<b>Nuttun:</b> Read about BCI paper in classroom (40%), Read and try to understand concept papers related about "Building Brain Invaders"<br> 
<br>
Brain invaders: https://www.youtube.com/watch?v=s73l8ZfQcWw <br>

# CP-DSAI-Project-EEG
<h3> Set up brain invader 2015 dataset </h3>
Repository with basic scripts for using the Brain Invaders 2015a dataset developed at the GIPSA-lab, in Grenoble. The dataset files and their documentation are all available at 

[https://zenodo.org/record/3266930](https://zenodo.org/record/3266930)<br>
https://github.com/plcrodrigues/py.BI.EEG.2015a-GIPSA<br>
The code of this repository was developed in **Python 3** using MNE-Python [1, 2] as tool for the EEG processing.

To make things work, you might need to install some packages. They are all listed in the `requirements.txt` file and can be easily installed by doing

```
pip install -r requirements.txt
```

in your command line. 

Then, to ensure that your code finds the right scripts whenever you do `import braininvaders2015a`, you should also do

```
python setup.py develop # because no stable release yet
```

Note that you might want to create a *virtual environment* before doing all these installations.

# References

[1] Gramfort et al. "MNE software for processing MEG and EEG data" [DOI](https://doi.org/10.1016/j.neuroimage.2013.10.027)

[2] Gramfort et al. "MEG and EEG data analysis with MNE-Python" [DOI](https://doi.org/10.3389/fnins.2013.00267)
