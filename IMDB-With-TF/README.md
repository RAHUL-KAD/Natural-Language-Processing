# IMDB movie reveiws using Tensorflow and keras

This model is already trained on Tensorflow's website. **Accuracy of the model** on the website is **0.8351** with **validation accuracy 0.7864.**

I achived the accuracy of 0.91 with 0.82 vlidation accuracy but it was **overfitting** so I used **dropout with Adamax optimizer** and again I achived accuracy
of **0.87** with **0.82 validation accuracy.**

## Parameters:
  
  - Number of neurons = 16
  - Number of hidden layers = 2
  - Droputout = 0.5
  - activation function = tanh
  - optimizer = Adamax
  - loss = binary_crossentropy
  - metrics = accuracy
  - epochs = 30

## Accuracy of the model:
![Screenshot from 2021-05-14 13-57-41](https://user-images.githubusercontent.com/63397654/118243768-6bc73200-b4bc-11eb-99a4-b0651fbff4e7.png)
