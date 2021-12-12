# FacExcerciseBook
Team:
-Bolla Gergő Levente-GGJKVS
-Schifferer András

Homework Project for Deep Learning. 
First milestone
We choose to use the FairFace dataset in our homework. (https://github.com/joojs/fairface)
We will provide a google drive link here so you can dowload the dataset through the google colab. (https://drive.google.com/drive/folders/1CPnuKVxtekzKgGzWLGDC6top2DcqgnNZ?usp=sharing). This also contains two .csv files where you can find the labels. We also used these in our code.
In this repo you can see two jupyter notebooks. One is a google colab notebook with the "open in colab" as requested. The other one is just a regular jupyter notebook that we worked inside during the project. 
Quick summary of the tasks that we've done: First we loaded all the images into 4 different subsets of npz format. This way of loading the data is more memory efficient. Here we made the pictures 128x128 pixels so it takes up less storage and we still can preserve most of the details in the picture. Next we loaded the labels and onehot encoded them so it's prepared for the CNN. Lastly we defined an image generator using TensorFlow/Keras so we will have more datapoints.

In the second milestone we changed a few things.
We embedded the images using keras FaceNet. 
We built a neural network and trained it.
We got 80% accuracy but it's still not the best as you can see on the prediction we provided.

In the final project we did hyperparameter optimization using keras-tuner.
We used hyperband because of pruning. We further trained the model and evaluated the results.
We also created a confusion matrix for visualization.
There is a PDF called Recognition-of-Facial-Features-with-Deep-Learning.pdf which is the description of the task we did during the semester.


Notebooks to use:
-DL_BHW_final is containing the final project with everything in it. 
 Drive link: https://drive.google.com/drive/folders/1CPnuKVxtekzKgGzWLGDC6top2DcqgnNZ?usp=sharing
 This drive contains the data to run the training.for this notebook
-Downloading_data notebook is a small notebook used to download and transfer the data to the Google drive.
 You don't have to run this because the files are in the drive link provided here
-The other notebooks are for different parts of the milestone project.(DL_big_Homework notebook is for the first. DL_Homework_trainingipynb is for the second.)

 
