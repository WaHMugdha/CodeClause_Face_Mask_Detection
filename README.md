# CodeClause_Face_Mask_Detection
Project number 2 as an Artificial Intelligence Intern at CodeClause. Detecting if the person in the image has a mask on their face or not.
### Dataset: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)https://www.kaggle.com/datasets/omkargurav/face-mask-dataset
#### This neural network is designed for binary image classification, where it takes input images with a size of 128x128 pixels and has two output classes.
* The neural network takes an input of RGB images of size (128, 128, 3) size.
* The images then go through Convolutional Layers with 32 filters, followed by 64 then 128 filters. The ReLU activation function is applied to the model. MaxPooling layer is used with a pool size of (2, 2)
* The output now is now 2D and is flattened to a 1D vector.
* The 1D vectors then go through Dense layers. The dropout layers are added to prevent overfitting.
* The output layer consists of 2 neurons for each class with the sigmoid activation function, which is used for binary classification.
