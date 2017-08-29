# About

This project objective is a attempt to solve the Kaggle challenge Planet: Understanding the Amazon from Space described on the following link
https://www.kaggle.com/c/planet-understanding-the-amazon-from-space

# Python dependencies

- numpy
- pandas
- matplotlib
- jupyter

Now, the specific stuff that I used:

- Keras: the neural network library.
- TensorFlow: keras uses one of them internally.
- tqdm: progress bar library.
- Seaborn: creates beautiful visualizations
- OpenCV: to deal with image transformations

# Running the code

The notebook file amazon-keras.ipynb includes all the source code 

Before running the notebook, use the link https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data to 
download the image data (in this project we used only the jpg images, the tiff were no use at all) and create 2 folders (/test-jpg and /train-jpg) and place the images inside each folder.
The test-jpg from kaggle should have 61191 jpg files and train-jpg should have 40480 jpg files.

To run the notebook just cd into the folder and use $ jupyter notebook
