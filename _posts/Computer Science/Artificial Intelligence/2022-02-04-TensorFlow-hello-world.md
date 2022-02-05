---
title:  "[TensorFlow] Get Started Neural Networks - Hello World"

categories:
  - AI
tags:
  - [Computer Science, TensorFlow]

toc: true
toc_sticky: true
 
date: 2022-02-04
last_modified_at: 2022-02-04
---
# Let's start Neural Network with TensorFlow

![TensorFlow](https://user-images.githubusercontent.com/79438062/152563680-7f2416b6-b4b0-4f9a-965a-e074b9c3f115.jpg)

## Setting Environment

I use [Google Colab](https://colab.research.google.com/) to use run the code. Colab is like a Jupyter Project in google drive with several useful libraries installed. Here is a simple introduction Youtube video for the `Google Colab` from TensorFlow.

{% include video id="inN8seMm7UI" provider="youtube" %}

## Simple Neural Network

### Import Library

When you write your code, you already know what are the rules. Then you make it into the code in the computer and let it solve the solution by following your code (rule). However, in Deep Learning with Neural Network, you need to train your neural network without knowing the rule. This means that you can make your computer figure out what are the rules based on the existing data.

```python
import tensorflow as tf
import numpy as np
from tensorflow import keras

print(tf.__version__)
```

> 2.7.0

- `import tensorflow as tf` allow you to import the TensorFlow library. By writing `as tf` at the end, you will start to call TensorFlow as `tf`.
- `import numpy as np`. This import numpy library and calling it as np. `numpy` is used to representing data easily in array and allow several numerical operations with optimzied function.
- `from tensorflow import keras` Keras is used to buliding a neural network. You need to import it from tensorflow to use it for neural network.
- `print(tf.__version__)` allow you to print out what version of TensorFlow you are currently using. From this example, we can find that my TensorFlow version is 2.7.0.

### Define and Compile

```python
# Define Keras Sequential Model
model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
# Compile the model
model.compile(optimizer='sgd', loss='mean_squared_error')
```

First of all, you need to define the `model` as Keras' Sequential. By using `[keras.layers.Dense(units=1, input_shape=[1])]`, you can set your Keras' Sequential class density as 1 layer and 1 neuron. Detail about the layer and neuron will be discussed in future posts. However, single dense layer is suitable in this post.

Next, you have to compile the defined model. There are two settings(`optimizer` and `loss`) you have to define your compiler. Detail explanation about the `optimzier` and the `loss` will be discussed in a future post. However, to make it simple, `loss` function shows how much your "learned" machine gives the incorrect answer from the given correct answer. In our code, we use `mean_squared_error` function calculating error. After looking at the result, the optimizer is used to make the next guess for the new answer and make the program more "learned". Its goal is reducing the `loss`. In this post, `sgd` (stochastic gradient descent) is used for the optimizer. You may find more options for the optimizers and find the details of each of them if you are interested.

Available optimizers in Keras:
- [SGD](https://keras.io/api/optimizers/#:~:text=Available%20optimizers-,SGD,-RMSprop)
- [RMSprop](https://keras.io/api/optimizers/#:~:text=SGD-,RMSprop,-Adam)
- [Adam](https://keras.io/api/optimizers/#:~:text=RMSprop-,Adam,-Adadelta)
- [Adadelta](https://keras.io/api/optimizers/#:~:text=Adam-,Adadelta,-Adagrad)
- [Adagrad](https://keras.io/api/optimizers/#:~:text=Adadelta-,Adagrad,-Adamax)
- [Adamax](https://keras.io/api/optimizers/#:~:text=Adagrad-,Adamax,-Nadam)
- [Nadam](https://keras.io/api/optimizers/#:~:text=Adamax-,Nadam,-Ftrl)
- [Ftrl](https://keras.io/api/optimizers/#:~:text=Nadam-,Ftrl,-Core%20Optimizer%20API)

### Training the Neural Network with Data

```python
# Declare the data for X and Y
xs = np.array([0.0, 1.0, 2.0, 3.0, 4.0, 5.0], dtype=float)
ys = np.array([-2.0, 1.0, 4.0, 7.0, 10.0, 13.0], dtype=float)
# Train the model
model.fit(xs, ys, epochs=500)
# Prediction
print("-------------------------------------------")
print("Prediction when x=10: ",model.predict([10.0]))
```

> Epoch 1/500 <br>
1/1 [==============================] - 0s 401ms/step - loss: 16.7694 <br>
Epoch 2/500 <br>
1/1 [==============================] - 0s 4ms/step - loss: 11.3999 <br>
Epoch 3/500 <br>
1/1 [==============================] - 0s 4ms/step - loss: 7.9341 <br>
Epoch 4/500 <br>
1/1 [==============================] - 0s 6ms/step - loss: 5.6948 <br>
Epoch 5/500 <br>
1/1 [==============================] - 0s 3ms/step - loss: 4.2455 <br>
Epoch 6/500 <br>
1/1 [==============================] - 0s 4ms/step - loss: 3.3051 <br>
Epoch 7/500 <br>
1/1 [==============================] - 0s 5ms/step - loss: 2.6927 <br>
Epoch 8/500 <br>
1/1 [==============================] - 0s 3ms/step - loss: 2.2916 <br>
Epoch 9/500 <br>
1/1 [==============================] - 0s 3ms/step - loss: 2.0266 <br>
Epoch 10/500 <br>
1/1 [==============================] - 0s 4ms/step - loss: 1.8495 <br>
... <br>
... <br>
... <br>
Epoch 496/500 <br>
1/1 [==============================] - 0s 4ms/step - loss: 0.0049 <br>
Epoch 497/500 <br>
1/1 [==============================] - 0s 3ms/step - loss: 0.0049 <br>
Epoch 498/500 <br>
1/1 [==============================] - 0s 6ms/step - loss: 0.0048 <br>
Epoch 499/500 <br>
1/1 [==============================] - 0s 3ms/step - loss: 0.0047 <br>
Epoch 500/500 <br>
1/1 [==============================] - 0s 6ms/step - loss: 0.0047 <br>
\<keras.callbacks.History at 0x7f8a278b9e10> <br>
------------------------------------------- <br>
Prediction when x=10:  [[27.780804]]

The data is provided to the system by defining `xs` and `ys`.

|:---:|---|---|---|---|---|
|**X**|0.0|1.0|2.0|3.0|4.0|5.0|
|**Y**|-2.0|1.0|4.0|7.0|10.0|13.0|

By writing `dtype=float`, we define that the given data is `float`. `float` means it is a real number and written in decimal point. For detail about `float`, you may refer to this [document](https://www.geeksforgeeks.org/python-float-type-and-its-methods/).

As we can see from the data, Y is changing its value as X changes with the following equation and rule.
\\[Y=(X*3)-2\\]

`model.fit(xs, ys, epochs=500)` train the model. By defining the number for `epochs` we can choose how many loops we want to make for training the model. As you can see from the output of the data, you may find that the loss decreases as the number of loops (Epoch) increases.

`model.predict([10.0])` use the trained model to guess what would be the result of Y when X is 10.0. Through our rule, we know that the Y value should be `28`. However, our trained model shows that the result is `27.780804`.

We can clearly see that the guessed number from our trained model is slightly lower than the expected number. However since the Neural Network is always dealing with the probability, it gives out the result that is higher probability when X is 10. Also, we only provided 6 sample data for training our model.

### Code
```python
import tensorflow as tf
import numpy as np
from tensorflow import keras

print(tf.__version__)

# Define Keras Sequential Model
model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
# Compile the model
model.compile(optimizer='sgd', loss='mean_squared_error')

# Declare the data for X and Y
xs = np.array([0.0, 1.0, 2.0, 3.0, 4.0, 5.0], dtype=float)
ys = np.array([-2.0, 1.0, 4.0, 7.0, 10.0, 13.0], dtype=float)
# Train the model
model.fit(xs, ys, epochs=500)
# Prediction
print("-------------------------------------------")
print("Prediction when x=10: ",model.predict([10.0]))
```

### Let's try with larger sample data and `epoch`

When `epoch` is changed from 500 to 1000 but the sample size is 6, the following prediction is made.
> Prediction when x=10:  [[27.988617]]

When the sample size is increased from 6 to 12 but `epoch` is 500, the following prediction is made.
> Prediction when x=10:  [[27.952002]]

When `epoch` is 1000 and the sample size is 12, the following prediction is made.
> Prediction when x=10:  [[27.997055]]

##### Reference
* <https://colab.research.google.com/github/https-deeplearning-ai/tensorflow-1-public/blob/master/C1/W1/ungraded_lab/C1_W1_Lab_1_hello_world_nn.ipynb>