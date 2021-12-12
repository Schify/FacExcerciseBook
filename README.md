# FacExcerciseBook
Team:
-Bolla Gergő Levente-GGJKVS
_Schifferer András-
Homework Project for Deep Learning. 
We choose to use the FairFace dataset in our homework. (https://github.com/joojs/fairface)
We will provide a google drive link here so you can dowload the dataset through the google colab. (https://drive.google.com/drive/folders/1CPnuKVxtekzKgGzWLGDC6top2DcqgnNZ?usp=sharing). This also contains two .csv files where you can find the labels. We also used these in our code.
In this repo you can see two jupyter notebooks. One is a google colab notebook with the "open in colab" as requested. The other one is just a regular jupyter notebook that we worked inside during the project. 
Quick summary of the tasks that we've done: First we loaded all the images into 4 different subsets of npz format. This way of loading the data is more memory efficient. Here we made the pictures 128x128 pixels so it takes up less storage and we still can preserve most of the details in the picture. Next we loaded the labels and onehot encoded them so it's prepared for the training. 
