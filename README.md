## Cats and Dogs classification
---------------------------------
In this project we write an algorithm that classify whether an image is cat or dog from the Cats and Dogs Dataset.


![Cats and Dogs Classification](catsandogs.jpg)

## Data

Creat a folder called Datasets, download Dataset from https://www.kaggle.com/tongpython/cat-and-dog. Put the data in the Dataset folder and run your code here.



## Important Information
----------------------------

    -Used Python Version: 3.6.0

    -install  modules with ```sudo pip3 install -r requirements.txt``` command.


   -----------------------------------------
## Model Architecture
    -Input Data Shape : 224*224*3
![cats and Dogs Classification](CatandDogs.png)  

I implemented a 2 layer convolutional neural network to classify images from the Cats and Dogs  Dataset.

I later implemented a 4 layer convolutional neural network on the same Dataset.

Activation function : Rectified Linear Unit (ReLU)

Max Pooling shape : 2 X 2

Classification : log_softmax

Optimizer : Gradient descent with Momentum

----------------------------------------------------
##  Projection (visualization) of the model is shown as:

![cats and Dogs Classification](Projection_Image.png)

-----------------------------------------------------------
## Images of Cats and Dogs Classification
![cats and Dogs Classification](Cat_and_Dog_Image1.png)

![cats and Dogs Classification](Cat-and_Dog_Image2.png)
![cats and Dogs Classification](CatandDogs_Image2.png)

---------------------------------------------------------
## Loss of the Model
![cats and Dogs Classification](Loss_Image.png)


Run FIle : python main.py

--------------------------------------

