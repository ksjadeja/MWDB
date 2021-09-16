# MWDB Phase-1 Project -    Feature Extraction and Finding K Similar Images


## Abstract
  In this phase of the project, we work on extracting various features from images, constructing vector models out of it and calculating similarity of images based on various distance metrics of the vectors. We are working on Olivetti faces dataset from sklearn.datasets which contains 400 facial images of 40 different persons with each person having 10 images of different orientations in grayscale and with all having same dimensions of 64x64. Our task is to extract various features from the data so that we can represent the images using less number of dimensions while still retaining important features. The main focus of this project is on three kinds of features, namely color moments that includes calculating mean, standard deviation and skewness of blocks of images, Histogram of Gradients (HOGs) and Extended Local Binary Pattern (ELBPs). Also these features are then converted to vectors and then we calculate similarity between images by implementing various distance metrics on these vectors and calculating the similarity score.
  

## Task 1
  def task1(choice, set_choice, image_choice)
    Choice denotes method i.e Color Moment, Hog or ELBP
    set_choice represents set number
    img_choice denotes image id
 Calculates feature vector based on given input and stores in folder Output/task1/task1.txt
 

## Task 2
  
 takes input from user the set number
 Calculates all three feature vectors for all images in the folder and saves them to Output/task2/task2.txt
 

## Task 3
  def task3(choice,set_choice,image_choice,k_choice):
    Choice denotes method i.e Color Moment, Hog or ELBP
    set_choice represents set number
    img_choice denotes image id
    k_choice denotes number of similar images to be found
  Calculates the given feature vector on the test image and all images on folder and calculates distance between the two
  We have used the correlation distance function.
  Then we sort in ascending order based on distance function and print first k similar images. 
  
  

    

## Task 4
  def task1(choice, set_choice, image_choice,k_choice)
    Choice denotes method i.e Color Moment, Hog or ELBP
    set_choice represents set number
    img_choice denotes image id
