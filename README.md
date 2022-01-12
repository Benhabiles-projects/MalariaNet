# MalariaNet
A generalized deep learning-based framework for assistance to the human malaria diagnosis from microscopic images

This project includes data and source code of our Plasmodium parasite diagnosis framework. The framework is based on segmentation and classification approches to analyse the  parasite from microscopic images of thin blood smear. The developped approaches exploits deep learning techniques to characterize the parasite shape and classifiy it among fours specises Falciparum, Malaria, Ovale and Vivax.

![image](https://user-images.githubusercontent.com/86927146/148984323-ce2b373f-44bc-411c-b5b1-d931350381ea.png) *Fig. 1 Overview of the proposed framework (first published in [1]).*



# How to use the code?
**Steps:**
> * Install required libraries (read **Requirements.txt** file for more details)
> * Download the project (repository) and unzip it.
> * Run the "MalariaDiagnosisAssistance.ipynb" file to characterize parasites and classify their species

**Notes:**
> * Code in "MalariaDiagnosisAssistance.ipynb" must be run cell by cell to generate required data for performing intermediate steps. 
> * The directory "malaria_data/" includes two samples of tests "dataset_1" and "dataset_2". The code "MalariaDiagnosisAssistance.ipynb" is setup to run by default on "dataset_2/test". To run it on "dataset_1/test", just replace in each cell the "dataset_2" word by "dataset_1"  
> * Each cell will permit to generate a set of images and save it into a specific directory in "test/". The tree structure of this directory and "malaria_data/" must be respected. For example, the cell "###Parasite Segmentation: binary mask generation###" will save a set of images corresponding to binary masks into a folder named "predict". For this reason an empty folder named predict must be created manually inside "test/".
> * Google Colab plateform with Tensorflow 1.15.0 (read **Requirements.txt** file for more details) could be exploited to run the code. In this case "malaria_data/" directory must be uploaded into the Google Colab session. 

# Datasets
The framework has been tested on 6 public datasets (dataset_1 to dataset_6). Details and references of these datasets are provided in Table 1 of the article referenced below. The samples provided in this repository namely "dataset_1/test" and "dataset_2/test" correspond to a small part of dataset_1 and dataset_2 referenced in the article.

# Team
**Project leaders:**

> * Halim Benhabiles, JUNIA, IEMN CNRS Lille, halim.benhabiles@junia.com
> * Ziheng Yang, JUNIA, IEMN CNRS Lille, ziheng.yang@junia.com

**Contributors:**

> * Karim Hammoudi, Université de Haute-Alsace, IRIMAS
> * Feryal Windal, JUNIA, IEMN CNRS Lille
> * Ruiwen He, JUNIA, IEMN CNRS Lille
> * Dominique Collard, LIMMS/CNRS-IIS, IRL 2820, The University of Tokyo, Lille, France

# How to cite this work?
[1] Yang, Z., Benhabiles, H., Hammoudi, K. et al. A generalized deep learning-based framework for assistance to the human malaria diagnosis from microscopic images. Neural Computing and Applications, Springer (2021). https://doi.org/10.1007/s00521-021-06604-4


