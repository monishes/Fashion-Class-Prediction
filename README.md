# Fashion-Class-Prediction
Predicting the class or the type of Fashion statement a person in an image is wearing using Convolutional Neural Networks.
This Convolutional Neural Network Architecture has the following Architecture :

1) Convoltional Layer - 64 Filters - (7 x 7) Kernel Size - "RelU" Activation Function
2) Max Pooling Layer - (2x 2) Kernel Size
3) Convoltional Layer - 128 Filters - (3 x 3) Kernel Size - "RelU" Activation Function
4) Convoltional Layer - 128 Filters - (3 x 3) Kernel Size - "RelU" Activation Function
5) Max Pooling Layer - (2x 2) Kernel Size
6) Convoltional Layer - 256 Filters - (3 x 3) Kernel Size - "RelU" Activation Function
7) Convoltional Layer - 256 Filters - (3 x 3) Kernel Size - "RelU" Activation Function
8) Max Pooling Layer - (2x 2) Kernel Size
9) Fully Connected Layer - 128 Units - "RelU" Activation Function
10) Dropout Layer - 50%
11) Fully Connected Layer - 64 Units - "RelU" Activation Function
12) Dropout Layer - 50%
13) Output Layer - 10 Units - "Softmax" Activation Function

This Architecture has an Accuracy of around 93%, this Project classifies the type of Fashion Statement worn by an individual in an input Image. This project classifies the attire into 10 Particular Classes of Fashion Statements as follows :

The Dataset for this project can be downloaded from : https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-Fashion-MNIST-Datasets.zip

0> T-Shirt/Top
1> Trousers
2> Pullover
3> Dress
4> Coat
5> Sandal
6> Shirt
7> Sneakers
8> Bag
9> Ankle Boots

The Results for the prediction are shown below :


![Screenshot 2022-08-31 133450](https://user-images.githubusercontent.com/57072184/188333832-3ab939d2-f2e0-49f5-91b9-43281bedba66.png)
![Screenshot 2022-08-31 133503](https://user-images.githubusercontent.com/57072184/188333834-9a465407-193d-4ced-9104-c5dfb00da494.png)
![Screenshot 2022-08-31 133517](https://user-images.githubusercontent.com/57072184/188333835-c41d3df9-c36a-4c2c-a1df-ab42e993ec43.png)
