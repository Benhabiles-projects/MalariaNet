# MalariaNet
A generalized deep learning-based framework for assistance to the human malaria diagnosis from microscopic images

This project includes data and source code of our Plasmodium parasite diagnosis framework. The framework is based on segmentation and classification approches to analyse the  parasite from microscopic images of thin blood smear. The developped approaches exploits deep learning techniques to characterize the parasite shape and classifiy it among fours specises Falciparum, Malaria, Ovale and Vivax.

# How to use the code?
**Steps:**
> * Download the project (repository) and unzip it.
> * Run the "MalariaDiagnosisAssistance.ipynb" file to characterize parasites and classify their species

**Notes:**
> * Code in "MalariaDiagnosisAssistance.ipynb" have to be run cell by cell to generate required data for performing intermediate steps. 
> * The directory "malaria_data/" includes two samples of tests "dataset_1" and "dataset_2". The code "MalariaDiagnosisAssistance.ipynb" is setup to run on "dataset_2". To run it on "dataset_1", just replace in each cell the "dataset_2" word by "dataset_1"  
> * Each cell will permit to generate a set of images and save it into a specific directory in "data_malaria/". The tree structure of this directory must be respected. For example, the cell "Parasite Segmentation: binary mask generation" will save a set of images corresponding to binary masks into a folder named "predict". For this reason an empty folder named predict must be created manually.
> * Google Colab plateform with Tensorflow 1.15.0 (read requirements.txt file for more details) my be exploited to run the code. In this case "malaria_data/" directory must be uploaded into the Google Colab session. 


