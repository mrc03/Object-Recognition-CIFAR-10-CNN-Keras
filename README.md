/*


    Author:: Raj Mehrotra
    Date:: 20-08-2018
*/







 
The famous CIFAR-10 dataset. 

The dataset contains of images of different objects like airplane, horse ,ship etc... that needs to be classified. 

The training set contains of 50000 images of 32*32 pixels each. Similarly the validation set contains 10000 images of  32*32 pixels too. 

I have used a self laid ConvNet to correctly classify the images into 10 classes each pertaining to one object. I have also used data augmentation using the ImageGenerator class provided in the Keras library to further increase the size of the training set and thus reduce overfitting chances. 

Finally I have used the ConvNet to make  predictions onto the validation set and achieved a decent accuracy of near about 85%.
