# Deep Learning with PyTorch
This is the code repository for [Deep Learning with PyTorch](https://www.packtpub.com/big-data-and-business-intelligence/deep-learning-pytorch?utm_source=github&utm_medium=repository&utm_campaign=9781788624336), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Deep Learning is powering the most intelligent systems in the world such as Google Voice, Siri, and Alexa. Advancements in powerful hardware such as GPU, software frameworks like PyTorch, Keras, Tensorflow, CNTK, etc and availability of big data have made it easier to implement solutions for various problems in the areas of Text, Vision, and advanced analytics.

This book will get you up and running with one of the most cutting-edge deep learning library—PyToch. Written in Python, PyTorch is grabbing the attention of all the data science professionals due to its accessibility and efficiency. You'll start off with installing PyTorch, then quickly move on to the various statistical operations with it. Next, you'll learn about Neural networks with PyTorch and we'll explore CNN, RNN, and LSTM.

This book provides the intuition behind the various state of the art Deep Learning architectures such as ResNet, DenseNet, Inception, and Seq2Seq without diving deep into the math of it. Then you will also learn about GPU computing during the course of the book. You will see how to train a model with PyTorch and dive into complex neural networks such as generative networks to produce text and images.

By the end of the book, you'll be able to implement PyTorch in deep learning applications with ease. You’ll also know everything it takes to get up and running with PyTorch.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
x,y = get_data() # x - represents training data,y -
represents target variables
w,b = get_weights() # w,b - Learnable parameters
for i in range(500):
y_pred = simple_network(x) # function which computes wx + b
loss = loss_fn(y,y_pred) # calculates sum of the squared differences of
y and y_pred
if i % 50 == 0:
print(loss)
optimize(learning_rate) # Adjust w,b to minimize the loss
```

All the chapters (except Chapter 1, Getting Started with Deep Learning Using PyTorch and Chapter 9, What Next) have associated Jupyter Notebooks in the book's GitHub repository.
The imports required for the code to run may not be included in the text to save space. You should be able to run all of the code from the Notebooks.
The book focuses on practical illustrations, so run the Jupyter Notebooks as you read the chapters.
Access to a computer with a GPU will help run the code quickly. There are companies such as paperspace.com and www.crestle.com that abstract a lot of the complexity required torun deep learning algorithms.

## Related Products
* [Hands-On Deep Learning with PyTorch](https://www.packtpub.com/big-data-and-business-intelligence/hands-deep-learning-pytorch?utm_source=github&utm_medium=repository&utm_campaign=9781788834131)

* [Advanced Deep Learning with Keras](https://www.packtpub.com/big-data-and-business-intelligence/advanced-deep-learning-keras?utm_source=github&utm_medium=repository&utm_campaign=9781788629416)

* [Deep Learning with TensorFlow - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/deep-learning-tensorflow-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788831109)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
