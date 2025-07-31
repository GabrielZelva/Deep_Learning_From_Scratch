# Deep Learning From Scratch

**Author**: Gabriel Pišvejc
**Contact**: gabrielzelva@gmail.com, [LinkedIn](https://www.linkedin.com/in/gabrielpisvejc/?profileId=ACoAADo5FU0BnBPkBj5SmMESVBJ633BazdnsESU)

In this small project of mine, I wanted to create a deep learning model from scratch, without using any external machine learning libraries like TensorFlow or PyTorch. The model predicts the autenticity of bank notes with ~99.78% accuracy. 

It was meant both as a learning exercise and as a demonstration of a ground-up understanding of how neural networks work internally. Everything I did is documented in the [Jupyter notebook](https://github.com/GabrielZelva/Deep_Learning_From_Scratch/blob/main/DeepLearningFromScratch.ipynb) in this repository, with working code and clear explanations of what it does and why. 
## Features

**Full manual implementation of**:
- The neural network structure
- Forward propagation
- Backward propagation
- Activation functions (ReLU, Logistic)
- Loss function and its derivatives (Square error)
- Stochastic gradient descent
- Training loop on a real-world dataset

**Network structure**:
- 4 Input nodes
- 2 Hidden layers of 16 nodes followed by a ReLU activation
- 1 Output node followed by a logistic function for binary prediction

**Libraries used**:
- NumPy
- Pandas
- SymPy
