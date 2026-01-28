# FaSHion-LW1-IMAGE-CLASSIFICATION

## Google Collab Link: [https://colab.research.google.com/drive/1ulXXIz0VfsSoTE2njhzKCzGIey7Surxq?usp=sharing](https://colab.research.google.com/drive/1ulXXIz0VfsSoTE2njhzKCzGIey7Surxq?usp=sharing)

## 1. What is the Fashion MNIST dataset?

  The Fashion MNIST dataset is like a big album of 70,000 small, black and white pictures of clothes, shoes, and bags. There are 10 different types of items, like t-shirts, trousers, and sneakers. It's used to teach computers how to recognize these clothing items, similar to how kids learn to identify different objects.


## 2.Why do we normalize image pixel values before training?

  If you give them really big numbers first, it's harder. But if you start with small numbers like 0 to 1, they learn faster and more accurately. Normalizing image pixel values from a wide range (0-255) to a small, consistent range (0-1) does something similar for our computer model. It helps the model learn more easily and quickly, preventing it from getting overwhelmed by large numbers and ensuring all parts of the image contribute fairly to its learning process.


## 3.List the layers used in the neural network and their functions.

  The neural network is like a sorting machine for clothes. First, the Flatten layer takes the square picture of a clothing item and unwraps it into a single long line of data. Next, the first Dense layer acts like a smart filter with 256 different detection units. It processes this line of data, picking out important features like edges or textures. Finally, the last Dense layer has 10 output units, one for each type of clothing (like T-shirt, shoe, or bag). This layer then decides which of these 10 categories the original picture most likely belongs to.


## 4.What does an epoch mean in model training?

  An epoch is like one full pass through all of your training data. Imagine you have a big textbook to study for an exam. One epoch means you've read the entire textbook from beginning to end once. During this process, the model learns from every example in the dataset, adjusts its internal settings (weights), and then moves on to the next epoch to read the textbook again, hopefully learning even more and improving its understanding each time.


## 5.Compare the predicted label and actual label for the first test image.

  For the very first test image, the model looked at the picture and predicted it was an 'Ankle boot'. When checked the actual label for that image, it was indeed an 'Ankle boot'.the model's predicted label for the first test image with its actual label, confirming if the prediction was correct, based on the executed cells' outputs.


## 6.What could be done to improve the model’s accuracy?

  Currently, the model uses a simple neural network with only one hidden layer. For image classification tasks, a Convolutional Neural Network (CNN) is typically much more effective. CNNs are designed to recognize patterns in images, which can significantly boost performance.
