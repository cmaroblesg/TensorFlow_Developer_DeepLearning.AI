# Augmentation: A technique to avoid overfitting
## Introduction
You've heard the term overfitting a number of times to this point. Overfitting is simply the concept of being over specialized in training -- namely that your model is very good at classifying what it is trained for, but not so good at classifying things that it hasn't seen. In order to generalize your model more effectively, you will of course need a greater breadth of samples to train it on. That's not always possible, but a nice potential shortcut to this is Image Augmentation, where you tweak the training set to potentially increase the diversity of subjects it covers. You'll learn all about that this week!

## [Google Colab](https://colab.research.google.com)
* [Colab FAQs](https://research.google.com/colaboratory/faq.html)

## Readings:
### Image Augmentation
You'll be looking a lot at Image Augmentation this week.\
Image Augmentation is a very simple, but very powerful tool to help you avoid overfitting your data. The concept is very simple though: If you have limited data, then the chances of you having data to match potential future predictions is also limited, and logically, the less data you have, the less chance you have of getting accurate predictions for data that your model hasn't yet seen. To put it simply, if you are training a model to spot cats, and your model has never seen what a cat looks like when lying down, it might not recognize that in future.\
Augmentation simply amends your images on-the-fly while training using transforms like rotation. So, it could 'simulate' an image of a cat lying down by rotating a 'standing' cat by 90 degrees. As such you get a cheap way of extending your dataset beyond what you have already.\
To learn more about Augmentation, and the available transforms, check out [https://github.com/keras-team/keras-preprocessing](https://github.com/keras-team/keras-preprocessing) -- and note that it's referred to as preprocessing for a very powerful reason: that it doesn't require you to edit your raw images, nor does it amend them for you on-disk. It does it in-memory as it's performing the training, allowing you to experiment without impacting your dataset.

### Start Coding...
Ok, now that we've looked at Image Augmentation implementation in Keras, let's dig down into the code.\
You can see more about the different APIs at the Keras site here: [https://keras.io/preprocessing/image/](https://keras.io/preprocessing/image/)
