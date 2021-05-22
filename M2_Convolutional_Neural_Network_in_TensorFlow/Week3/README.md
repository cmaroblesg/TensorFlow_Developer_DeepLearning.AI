# Transfer Learning
## Introduction
Building models for yourself is great, and can be very powerful. But, as you've seen, you can be limited by the data you have on hand. Not everybody has access to massive datasets or the compute power that's needed to train them effectively. Transfer learning can help solve this -- where people with models trained on large datasets train them, so that you can either use them directly, or, you can use the features that they have learned and apply them to your scenario. This is Transfer learning, and you'll look into that this week!

## [Google Colab](https://colab.research.google.com)
* [Colab FAQs](https://research.google.com/colaboratory/faq.html)

## Coding Assignment
* [Exercise 3 - Horses vs. humans using Transfer Learning](./codes/Exercise_3_Horses_vs_humans_using_Transfer_Learning_Question-FINAL.ipynb)

## Colab_Codes
* [Course 2 - Part 6 - Lesson 3 - Notebook](./Colab_Codes/Course2-Part6-Lesson3-Notebook.ipynb)
* [Course 2 - Part 6 - Lesson 3 - Notebook v2](./Colab_Codes/Course2-Part6-Lesson3-Notebook_v2.ipynb)
* [Exercise 7 - Question](./Exercises/Exercise7-TransferLearning/Exercise7-Question.ipynb)

## Readings
### Start coding!
Now that we've seen the concepts behind transfer learning, let's dig in and take a look at how to do it for ourselves with TensorFlow and Keras.\
In the next few videos you'll be using this notebook to explore transfer learning: [https://colab.research.google.com/github/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%206%20-%20Lesson%203%20-%20Notebook.ipynb](https://colab.research.google.com/github/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%206%20-%20Lesson%203%20-%20Notebook.ipynb)\
For more on how to freeze/lock layers, explore the documentation, which includes an example using MobileNet architecture: [https://www.tensorflow.org/tutorials/images/transfer_learning](https://www.tensorflow.org/tutorials/images/transfer_learning)

### Using dropouts!
Another useful tool to explore at this point is the Dropout.\
The idea behind Dropouts is that they remove a random number of neurons in your neural network. This works very well for two reasons: The first is that neighboring neurons often end up with similar weights, which can lead to overfitting, so dropping some out at random can remove this. The second is that often a neuron can over-weigh the input from a neuron in the previous layer, and can over specialize as a result. Thus, dropping out can break the neural network out of this potential bad habit!\
Check out Andrew's terrific video explaining dropouts here: [https://www.youtube.com/watch?v=ARq74QuavAo](https://www.youtube.com/watch?v=ARq74QuavAo)
