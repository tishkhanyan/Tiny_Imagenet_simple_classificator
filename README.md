# Tiny_Imagenet_simple_classificator

I've implemented a simple classifier for the 100000 64x64x3 pics of 200 classes from the Tiny Imagenet dataset. 
This classifier is super simple and is using transfer learning: ResNet18 as a feature extractor and one fully connected layer on it. That's it! 
Seems that it is giving >50% accuracy on validation dataset in only 5 epochs (trained on GPU takes around 2 mins/epoch).
