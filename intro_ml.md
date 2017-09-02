** Machine learning tasks 

We have two basic machine learning tasks: classification and regression. 

** Classification

Definition of classification: given a feature vector v of case x, determine x belongs to class A or class B. 

e.g. Given the spectrum v of a piece of sound x, determine x belongs to human voice A or white noise B 

You can see the output of classification is descrete. 

** Regression

The other task is regression: 

Given the features v of x, y is a random variable who's input is x, determine y. 

A special case of regression is that y = x

e.g. Given the truncated spectrum v of human voice x, recover x. 

or more general:

e.g. Given the truncated spectrum v of human voice x, determine x's father's voice y. 

You can see that the output of regression is continuous.

The input format does not matter. It can be descrete or continuous, or the mixture. Different ML models handle different input format. Typically, deep learning models usually assume the input is continuous. If it is descrete (like language), we have ways to transform descrete inputs into continuous representation. This is called "embedding" and it is one kind of Representation Learning. 

** Perspective of regression and classification: 

We can view Regression as the continuous version of classification.

All machined models are about regression and classification.

Now we will focus on classification. 

** Machine learning models. 

We start from the very simple linear model. 

Suppose x is a human voice, v is its spectrum. We want to classify x, and determine whether x is a man or a woman. 

Since v is the spectrum vector, or more precisely a sequence if spectrums. For simplicity we only choose one time step of the sequence. Then v is a vector. In the sequence case it should be a sequence of vectors. We will cover the sequence case in the RNN section. Now one can imagine v is the spectrum of a vowel like "e" which best discriminates the gender. 

To determine the class c of v, in the linear model we choose another parameter vector w and do the dot product o = v • w. Suppose w is so good that all o of man will larger than 0 and all o of women will less than 0. Then we have the conclusion:  v = specturm, w = model parameter, o = v • w, if o > 0, then this is a voice of a man, else o < 0, a woman.

Do no underestimate this simplicity. In many cases it performs fairly well, if we choose the right w.

So the question is: how to find w ?

** Training and testing

We find the best w from a large set of data.

Suppose we have 1. a perfect dataset that covers all v of human voice, and they are annotated with golden o. 2. A new voice v1, and we want to find w from the perfect, use the w to predict v1, and get o1

The process of finding w from the dataset is called training.

The process of predicting o1 is called testing.

Training and Testing is the two typical phases of machine learning.

** Methods to train w

There are a variety of ways, but the most popular way is called the stochastic gradient descent or SGD.

Normally I should follow the convention and tell you what SGD is, but I will not do that because there are better materials.

This tutorial only aims to tell you what the basical machine learning idea is. You may want to repeat the key words again now: Classification, Regression, Training and Testing. And now you get it.

Trust me you will come back to these ideas again and again. 

The reason I introduce the linear model is that it is the very basic structure of neural network, or deep learning.

Now you can start from Standford Udlfl. Good luck.

** One more thing

What if we add a non-linear activation function tanh to the linear model like this: o = tanh(wv) ? 

Tanh is the hyporbolic tangent. If the input is less than 0, then its output is almost -1. If the input is larger than 0, its output is almost 1. It looks like this function is sleeping on the negative input. But if your input is larger than 0, it is suddenly activated.

This is the very basic idea of a single neuron.

Neuron networks is nothing but a bunch of neurons connected with each other.

