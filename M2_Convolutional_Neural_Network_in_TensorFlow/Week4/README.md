# Multiclass classification

## Introduction
You've come a long way, Congratulations! One more thing to do before we move off of ConvNets to the next module, and that's to go beyond binary classification. Each of the examples you've done so far involved classifying one thing or another -- horse or human, cat or dog. When moving beyond binary into Categorical classification there are some coding considerations you need to take into account. You'll look at them this week!

## Readings
### Introducing the Rock-Paper-Scissors dataset
#### [http://www.laurencemoroney.com/rock-paper-scissors-dataset/](http://www.laurencemoroney.com/rock-paper-scissors-dataset/)
Rock Paper Scissors is a dataset containing 2,892 images of diverse hands in Rock/Paper/Scissors poses. It is licensed [CC By 2.0](https://creativecommons.org/licenses/by/2.0/) and available for all purposes, but it’s intent is primarily for learning and research.\
Rock Paper Scissors contains images from a variety of different hands,  from different races, ages and genders, posed into Rock / Paper or Scissors and labelled as such. You can download the training set [here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip), and the test set [here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps-test-set.zip). These images have all been generated using CGI techniques as an experiment in determining if a CGI-based dataset can be used for classification against real images. I also generated a few images that you can use for predictions. You can find them [here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps-validation.zip).\
Note that all of this data is posed against a white background.\
Each image is 300×300 pixels in 24-bit color\
You'll see how this dataset can be used to build a multi-class classifier in the next video.
