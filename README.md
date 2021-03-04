Introduction
A home electronics company which manufactures state of the art smart televisions wants to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command as follows (ordered as per there category number):

0. Left swipe: 'Jump' backwards 10 seconds
1. Right swipe: 'Jump' forward 10 seconds
2. Stop: Pause the movie
3 Thumbs down: Decrease the volume
4. Thumbs up:  Increase the volume

Business Objective
Build an AI model that can reside in the webcam memory and successfully classify the user gestures into one of the 5 aforementioned categories. Based on the gesture the smart-TV will perform certain task. During implementation the model complexity needs to be optimal considering the performance and response time trade-off in real time.

Analytical Objective
Build a CNN based image classification model that is successfully able to classify the videos (available as stream of images) into one of the five gestures to be able to perform a certain downstream task. While implementing the model parameters should be optimal (lite AI model) allowing deployment onto the webcam memory.
