# Dogs and Cat classifier.

Along with cloning this repository. Clone this repository [https://github.com/fchollet/deep-learning-models](https://github.com/fchollet/deep-learning-models). 

Dependencies:

* keras
* tensorflow/theano
* numpy
* matplotlib
* bcolz
* pillow
* h5




Files:

1. image classifier in **7 step** . ipynb :

      * Predicts image offline.
      * Image must be one of 1000 categories in imagenet dataset. 

2.  **CNN - 1**. ipynb:
     * Notebook contains:
        1. Simple convolutional architecture:
            * 1 convolution layer
            * 1 maxpooling layer
            * 1 flatten layer
            * 1 dense layer

     * Ran on small dataset. 
     * **Saved** the architecture in h5 format. 

3. **CNN - 2** . ipynb:
    * **Loaded** the architecture.
    * Predicting the image. 

4. ### Vgg architecture from scratch . ipynb:
    * Created vgg-16 cnn architecture from scratch.
    * Architecture contains:
         1. convolution layers with zero padding layer. 
         ( several convolution layers with varying no of filters. Maxpooling layer in between)
         2. Flatten layer
         3. 2 Dense layers.
         4. 3rd dense layer with 1 ouput for cats and dogs ( in original there are 1000 outputs )
    * Tried to saved the model. 

5. ### Advanced vgg architecture . ipynb:
   * **Splitting** the convolutional computation part & remaining part of the model.
   * used **bcolz** for faster run time. 
   * Reduced **underfitting**:
       * Removal/reduced dropout.
   * Reduced **overfitting**:
       * Data Augmentation.
       * Batch Normalization. 

6. ### Fine tuning and Back Propagation:
     * Fine tuning is to modify existing model and create a **secondary model**. 
     * Doing Back Propagation in **few** lines  
            
       
   