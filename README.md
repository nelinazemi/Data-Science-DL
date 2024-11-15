# Data-Science Projects using DL
![Neural_Networks_2880x1620-2880x1620-ezgif com-webp-to-jpg-converter](https://github.com/nelinazemi/Data-Science-DL/assets/113586221/0c867883-70cd-496f-8de1-82b7eb4828de)
#### Welcome to my repo containing data science projects on various topics, showcasing knowledge in Deep Learning and the ability to apply it to real-world complex models.

## Projects:
- ### 1- [Multi-Layer Perceptron (MLP) for Classification:](https://github.com/nelinazemi/Data-Science-DL/tree/f29a2b9145ae41fcc3aa59e89c7f866f4b3fa7a8/Multilayer%20Perceptron%20(MLP)%20Implementation/MLP%20for%20Classification)
    - This project focuses on predicting the price range of mobile phones based on various features using a neural network model.
    - A MLP model is defined with two hidden layers. The model is moved to a GPU if available.
    - The model is trained using Stochastic Gradient Descent (SGD) as the optimizer and Cross-Entropy Loss as the loss function.
    - The model's performance is evaluated on the validation set.survived or not based on the given features with a high degree of accuracy.
      
- ### 2- [Multi-Layer Perceptron (MLP) for Regression:](https://github.com/nelinazemi/Data-Science-DL/tree/f29a2b9145ae41fcc3aa59e89c7f866f4b3fa7a8/Multilayer%20Perceptron%20(MLP)%20Implementation/MLP%20for%20Regression)
  - This project focuses on predicting the median house value based on various features using a neural network model.
  - The model is trained using Stochastic Gradient Descent (SGD) as the optimizer and Mean Squared Error (MSE) as the loss function. The training process involves calculating the loss for each batch of data and updating the model parameters.
  - The model's predictions on the test set are compared with the actual values to compute the R-squared score.
    
- ### 3- [RNN-based Neural Networks:](https://github.com/nelinazemi/Data-Science-DL/tree/9e32698c3f5523395d28f4485011af1fd84d83ff/Recurrent%20Neural%20Network)
  - This folder contains three types of neural network models: LSTM (Long Short-Term Memory), RNN (Recurrent Neural Network), and TNN (Tensorial Neural Network). These models have been trained on the UCI-HAR (Human Activity Recognition Using Smartphones) dataset. The UCI-HAR dataset consists of recordings from the accelerometers and gyroscopes of smartphones worn by 30 participants while performing six different activities: walking, walking upstairs, walking downstairs, sitting, standing, and laying. The dataset includes a 561-feature vector with time and frequency domain variables1.
  - Neural Network Models:
  
        - LSTM (Long Short-Term Memory): LSTM networks are a type of RNN designed to handle long-term dependencies and mitigate the vanishing gradient problem. They are particularly effective for sequential data and time series prediction.
        - RNN (Recurrent Neural Network): RNNs are a class of neural networks that process sequential data by maintaining a hidden state that captures information from previous time steps. They are commonly used for tasks such as text, speech, and time series analysis.
        - TNN (Tensorial Neural Network): TNNs combine the principles of tensor networks and neural networks to handle high-dimensional data efficiently. They are used for tasks such as network compression, information fusion, and quantum circuit simulation.

- ### 4- [Generative Adversarial Network:](https://github.com/nelinazemi/Data-Science-DL/tree/aaa46ff4aebc1e73fd2ae1f1a3d89e000056be44/Generative%20Adversal%20Network)
    - In this project the MNIST dataset was used to implement both the generator and discriminator parts of GAN neural network from scratch.
    - GANs are a class of machine learning frameworks where two neural networks, a generator and a discriminator, compete against each other to produce data that is indistinguishable from real data.
    - The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. It contains 60,000 training images and 10,000 testing images of digits from 0 to 9.

- ### 5- [Audio Processing Project:](https://github.com/nelinazemi/Data-Science-DL/tree/a51c6a737db847af01863dd616e64b70b4dbb059/Audio%20Processing)
    - This project was aimed to classify sounds using a custom dataset with a few sound samples.
    - An MS neural network was implemented from scratch to achieve this goal.
    - The data transformation was carried out using various functions of torchaudio.


- ### 6- [Natural Language Processing:](https://github.com/nelinazemi/Data-Science-DL/tree/b0f3462ee3b9cfcbdbf05a076017254e06012ad8/Natural%20Language%20Processing)
	- This project demonstrates natural language processing (NLP) techniques using PyTorch and TorchText. 
	- It includes data preprocessing, tokenization, vectorization with GloVe embeddings, and classification tasks using the AG News dataset.
	- The code explores embeddings, embedding bags, and transformations, while also building and training an RNN-based classifier. Various training strategies, optimization methods, and evaluation metrics are implemented to improve the model's performance.
	- The project concludes with visualizations of the loss and accuracy across training epochs.

- ### 7- [Knowledge Distillation:](https://github.com/nelinazemi/Data-Science-DL/tree/635dcf9e240e542443ebcfc2669524c69acd719f/Knowledge%20Distillation)
	- This code implements a knowledge distillation workflow for image classification on the CIFAR-10 dataset.
	- It defines Teacher and Student models, with the Teacher being a deeper network and the Student being a shallower one.
	- Using data augmentation techniques and DataLoaders, it trains the Teacher model first, optimizing its performance with multiple hyperparameter tuning steps (learning rate, weight decay).
	- The knowledge distillation loss function combines KL Divergence to mimic the Teacher's soft labels and Cross-Entropy Loss to align with true labels.
	- The Student model is trained with the Teacher's guidance, aiming to achieve comparable accuracy with fewer parameters. Finally, the training and validation performance is visualized, showcasing loss and accuracy trends across epochs.
