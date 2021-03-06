# Project Guideline<br>
* CNN3D.ipynb
  * This is code for 3D CNN Model
* SVM.ipynb
  *  This is code for the SVM model
* Model-CM-CW-CNN.ipynb
  * This is a code for CM-CW-CNN
* Parallel_CNN.ipynb
  * This is a code for parallel CNN model

# Work Log

<b> [Week 6 : 15-19 Nov 2021]</b> <br>
In this week, out group focus on model implementation for comparison.
<br> <br>
<b>Pasit:</b> Implement CNN model from paper [9][10] and testing it. <br>
<b>Saratoon:</b> Implement SVM model according to this paper[11]. Also try learning more about Xdawn preprocessing method and experiment it with the SVM model. <br>
<b>Nopphawan:</b> Try to learn and understand more about PCA method. Minorly modify the code of CM-CW-CNN model. <br>
<b>Nuttun:</b> Try to modify the CNN model which is parallel convolutional neural network. Also read material related to PCA precprocessing data.  <br>

<br>

<b> [Week 5 : 8-12 Nov 2021]</b> <br>
In this week our group focus on implement the model to for comparision based on refernce papers. We decide to use PCA as our based preprocessing. For model, we use CNN and 3D CNN for testing.<br> <br>
<b>Pasit:</b> Implement 3D convolution network from paper [9][10]. As the 3d CNN from model show that with 3d CNN EEG, it can improve the accuracy for classification.<br>
<b>Saratoon:</b>  Read more about PCA and implement it. Experiment with the model to see how much accuracy has changed.<br>
<b>Nopphawan:</b> Implement and modify the CM-CW-CNN model to classify 3 classes of output. Try to test the model and get very satisfactory accuracy. <br>
<b>Nuttun:</b> Implement PCA-CNN from paper [5]. Experiment the model and try to following and modifying the model.  <br>

<br>

<b> [Week 4 : 1-5 Nov 2021]</b> <br>
In this week we focus doing research about possible model and baseline model comparison paper to find model that could get best result for p300 brain invader eeg signal. And we also want to compare about PDA and LDA in precprocessing whether the accuracy will improve or not. Based on [5] paper, it said that if we use PDA or LDA in the preprocessing it can get better result in accuracy. We also testing CNN model implementation and get accuracy about 79%. We use CNN model structure same as in the paper [3]. We also assign papers seperately to each member and then we disscuss about it together. In the next week we will design the experiment process try to apply PCA and LDA to preprocessing to check wether the result will improve or not.<br> <br>
<b>Pasit:</b>  In this week I read about PREP data preprocessing pipeline[6] in order to understand the process of feature selection and I also research about possible RNN LSTM model[7], then I find the comparison between CNN and RNN[8]. The result from comparation[8] show that CNN can get better accuracy than RNN, so we decide to use CNN as our base model.<br>
<b>Saratoon:</b> Read about Independent Component Analysis for EEG Data
Preprocessing - Algorithms Comparison[4].This paper is about comparing the accuracy of the model using each ICA algorithms and the model that didn't use ICA. It turns out that the results are about the same. <br>
<b>Nopphawan:</b> Read a paper[3] that is about P300 based character recognition using convolutional neural network. Channel mixing (CM) and Channel wise (CW) were presented in the paper and comparation between CNN, CW-CM-CNN-ESVM, 2D-CNN-ESVM, CM-CW-CNN-ESVM show that the highest accuracy can be obtained from CM-CW-CNN-ESVM model. Then, I try to implement a model to use with selected dataset by following CM-CW-CNN model. <br>
<b>Nuttun:</b> Read A Novel P300 Classification Algorithm Based on a Principal Component Analysis-Convolutional Neural Network[5]. This papar talk about the selected preprocessing data that is PCA. Morever, comparing the model which are CNN, BN3 and SVM. <br>

<br>

<b> [Week 3 : 25-29 Oct 2021]</b> <br>
Right now we can download and import the dataset into our project. Then we plot it and discuss about the signal that we have get. Reading more about noise in EEG wave. In this week we focus on how to preprocessing dataset for training. Find method to remove unnecessary chanel. <br> <br>
<b>Pasit:</b> Reading about preprocessing pipeline HAPPE method. Try to understand the noise in EEG process and how to reduce it. Find possible model for training. <br>
<b>Saratoon:</b> try to preprocess the data by following the example and try to understand the code as well as find more info about each preprocessing step. <br>
<b>Nopphawan:</b> try to understand code how to preprocess data, read more papers to understand brain invaders. <br>
<b>Nuttun:</b> try to understand code (CON2D) available on github. finding the preprocessing data and read more the document related to mne library.<br>

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

[3] Sourav K. and Samit A., "P300 based character recognition using convolutional neural network" [DOI](https://doi.org/10.1016/j.bspc.2019.101645)

[4] [Independent Component Analysis for EEG Data Preprocessing - Algorithms Comparison](https://link.springer.com/content/pdf/10.1007%2F978-3-642-40925-7_11.pdf)

[5] Feng L. et al., "A Novel P300 Classification Algorithm Based on a Principal Component Analysis-Convolutional Neural Network" [DOI](https://doi.org/10.3390/app10041546)

[6] The PREP pipeline: standardized preprocessing for large-scale EEG analysis [DOI](https://doi.org/10.3389/fninf.2015.00016)

[7] [Recurrent Neural Networks for P300-based BCI](https://arxiv.org/pdf/1901.10798.pdf)

[8] [Comparison of Convolutional and Recurrent Neural Networks for the P300 Detection](https://www.scitepress.org/Papers/2021/102482/102482.pdf)

[9] Convolutional Neural Networks with 3D Input for P300 Identification in Auditory Brain-Computer Interfaces [DOI](https://doi.org/10.1155/2017/8163949)

[10] Joshi R., Goel P., Sur M., Murthy H.A. (2018) Single Trial P300 Classification Using Convolutional LSTM and Deep Learning Ensembles Method. In: Tiwary U. (eds) Intelligent Human Computer Interaction. IHCI 2018. Lecture Notes in Computer Science, vol 11278. Springer, Cham. [DOI](https://doi.org/10.1007/978-3-030-04021-5_1)

[11] Sourav K., Samit A. (2017) P300 Detection with Brain-Computer Interface Application using PCA and Ensemble of Weighted SVMs [Link](https://www.researchgate.net/profile/Sourav-Kundu-4/publication/319504119_P300_Detection_with_Brain-Computer_Interface_Application_Using_PCA_and_Ensemble_of_Weighted_SVMs/links/59db54ca0f7e9b2f587fe4a0/P300-Detection-with-Brain-Computer-Interface-Application-Using-PCA-and-Ensemble-of-Weighted-SVMs.pdf)
