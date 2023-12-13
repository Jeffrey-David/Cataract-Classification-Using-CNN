# Cataract-Classification-Using-CNN
Cataract Classification Model using Ocular Disease recognition and cataract datasets


## IMPLEMENTATION
The implementation is done in Google Colabs. The language used to implement the project is python. 

![Implementation](https://github.com/Jeffrey-David/Cataract-Classification-Using-CNN/assets/66271004/5708db97-d303-499d-b39c-62417d1781a4)

### A.	Dataset
In this project we use two datasets to train the CNN model. The first dataset used is cataract dataset which is a dataset of retinal images of four categories:

(i)	Normal

(ii)	Cataract

(iii)	Glaucoma

(iv)	Retina disease

It consists of 601 retina images that can be used to train the Deep learning model. 

The second dataset used is Ocular Disease Recognition Dataset. It is a structured database of 5000 patients with colour fundus photographs of right and left eyes, age, and the result of the diagnosis. The patients are classified into eight labels Normal, Diabetes, Glaucoma, Cataract, Macular Degeneration, Hypertension, Pathological Myopia and other abnormalities.


## Algorithm

1.	Import the libraries that are needed for training the CNN model.

2.	Import the two datasets and initialize the paths to the datasets.

3.	Process the cataract dataset. The other diseases that are present in the dataset are removed and only the cataract disease is added to the dataframe.

4.	Process the Ocular Disease Recognition Dataset and create a dataframe with only cataract disease and normal labelled data. Reduce the number of normal labelled data so that there is no bias in the dataset. 

5.	Concatenate both the data frames and create the complete dataset that is used to train the model.

6.	Divide the dataset into train, test and validation dataset. The test dataset is 20 percent of
the original dataset. The validation dataset is 15 percent of the training dataset.

7.	Resize all the images to a standard size.

8.	Set the parameters for the Convolution 2D keras classifier and train the model with epochs=100.

9.	Finally evaluate the model using accuracy and loss.
 

