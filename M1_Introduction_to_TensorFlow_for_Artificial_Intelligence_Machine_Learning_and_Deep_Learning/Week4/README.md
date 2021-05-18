## Using Real-world Images

## Introduction
Last week you saw how to improve the results from your deep neural network using convolutions. It was a good start, but the data you used was very basic. What happens when your images are larger, or if the features aren’t always in the same place? Andrew and Laurence discuss this to prepare you for what you’ll learn this week: handling complex images!

## [Google Colab](https://colab.research.google.com)
* [Colab FAQs](https://research.google.com/colaboratory/faq.html)

## Coding assignment
* [Exercise 4: Handling complex images](./codes/Exercise4-Question.ipynb)

## Colab_Codes
* [Experiment with the horse or human classifier](./Colab_Codes/Course1-Part8-Lesson2-Notebook.ipynb)
* [Get hands-on and use validation](./Colab_Codes/Course1-Part8-Lesson3-Notebook.ipynb)
* [Get Hands-on with compacted images](./Colab_Codes/Course1-Part8-Lesson4-Notebook.ipynb)
* [Exercise 4: Handling complex images](./Exercises/Exercise4-HandlingComplexImages/Exercise4-Question.ipynb)

# Readings
## Explore an impactful, real-world solution
As Andrew and Laurence discussed, the techniques you’ve learned already can apply to complex images, and you can start solving real scenarios with them.
They discussed how it could be used, for example, in disease detection with the Cassava plant, and you can see a video demonstrating that [here](https://www.youtube.com/watch?v=NlpS-DhayQA).
Once you’ve watched that, move onto the next lesson!

## Designing the neural network
Now that you’ve seen how an ImageGenerator can flow images from a directory and perform operations such as resizing them on the fly, the next thing to do is design the neural network to handle these more complex images. You’ll see that in the next video.

## Train the ConvNet with ImageGenerator
Now that you’ve designed the neural network to classify Horses or Humans, the next step is to train it from data that’s on the file system, which can be read by generators. To do this, you don’t use model.fit as earlier, but a new method call: model.fit_generator. In the next video you’ll see the details of this.

## Training the neural network
Now that you’ve learned how to download and process the horses and humans dataset, you’re ready to train. When you defined the model, you saw that you were using a new loss function called [‘Binary Crossentropy’](https://gombru.github.io/2018/05/23/cross_entropy_loss/), and a new [optimizer](https://www.tensorflow.org/api_docs/python/tf/train/RMSPropOptimizer) called [RMSProp](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf). If you want to learn more about the type of binary classification we are doing here, check out [this](https://www.youtube.com/watch?v=eqEc66RFY0I&t=6s) great video from Andrew!

## Experiment with the horse or human classifier
Now it’s your turn. You can find the notebook [here](https://colab.sandbox.google.com/github/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%202%20-%20Notebook.ipynb). Work through it and get a feel for how the ImageGenerator is pulling the images from the file system and feeding them into the neural network for training. Have some fun with the visualization code at the bottom!

In earlier notebooks you tweaked parameters like epochs, or the number of hidden layers and neurons in them. Give that a try for yourself, and see what the impact is. Spend some time on this.

Once you’re done, move to the next video, where you can validate your training against a lot of images!

## Get hands-on and use validation
Now you can give it a try for yourself. [Here’s](https://colab.sandbox.google.com/github/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%203%20-%20Notebook.ipynb) the notebook the Laurence went through in the video. Have a play with it to see how it trains, and test some images yourself! Once you’re done, move onto the next video where you’ll compact your data to see the impact on training.

## Get Hands-on with compacted images
Try [this](https://colab.sandbox.google.com/github/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%204%20-%20Notebook.ipynb) version of the notebook where Laurence compacted the images. You can see that training times will improve, but that some classifications might be wrong! Experiment with different sizes -- you don’t have to use 150x150 for example!

# Week 4 Resources
You used a few notebooks this week. For your convenience, or offline use, I've shared them on GitHub. The links are below:
* [Horses or Humans Convnet](https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%202%20-%20Notebook.ipynb)
* [Horses or Humans with Validation](https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%203%20-%20Notebook.ipynb)
* [Horses or Humans with Compacting of Images](https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%204%20-%20Notebook.ipynb)
