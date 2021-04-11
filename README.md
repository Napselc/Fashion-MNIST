# Fashion-MNIST

Fashion MNIST is a popular dataset used by deep-learning-model developers to set benchmarks. Following are the details of the implementation:

1. Dataset source: https://github.com/zalandoresearch/fashion-mnist

2. Platform: Jupyter Notebooks

3. Neural Network used: Tensorflow's Sequential
      Hyperparameters:
        1.Epochs- 50
        2.Batch Size- 1000

4. Layers Used: 
    
    A) 2-D Convolution Layer_1
        Hyperparameter: 
         1. Filters- 20
         2. Size- 5 X 5
         3. Activation- Rectified Linear Unit(relu)
         
    B) Max Pooling Layer
        Hyperparameters:
          1. Size- 2 X 2
          
    C) 2-D Convolution Layer_2
        Hyperparameter: 
         1. Filters- 10
         2. Size- 5 X 5
         3. Activation- Rectified Linear Unit(relu)
    
    D) Flatten
    
    E) Dense
        Hyperparameter: 
         1. Units- 10
         2. Activation- Softmax

Model Summary:

![image](https://user-images.githubusercontent.com/31684198/114301429-7586ff80-9ae2-11eb-8828-178bf3055a85.png)

Results:

Testing Set Accuracy: 0.8838
         
        
