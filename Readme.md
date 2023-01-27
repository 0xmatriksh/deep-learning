## Deep Learning Implementations

This is the repo consisting implementation of deep learning. 

Open the folder to read more

It uses `keras` library from `tensorflow`

To create the model:

```
model = Sequential()  # Sequential is imported from tensorflow.keras
```

And to create the layers, `Dense` is imported from keras.layers
```
model.add(Dense(10, activation="relu"))
```

Activation like relu, sigmoid, softmax are used.

`model.summary()` can be used to check the models overall summary

`model.compile()` is used to compile the model which requires loss function as parameter

Loss function can be mse, binary_crossentropy, categorical_crossentropy

`model.fit()` is used to fit by passing X_train,y_train and epochs can be passed as no. of iters

Finally,
`model.predict()` to predict the output