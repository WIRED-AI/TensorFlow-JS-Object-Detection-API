# TensorFlow-JS-Object-Detection-API

A simple user interface for TensorFlow's Open Source Object Detection Model. No server or backend processing was used for moving the images to the folder(This project is totally based
on image source in the form of an url instead of using a local file from the client)

Accepts url to an image and appends it to the html body and makes an asynchronous call to the TensorFlow's mobilenet Model on clicking the button "Get Result"

Upon receiving response from mobilenet model. The results will be appended at the bottom of every image.

Based on the test results, the accuracy was quite convincing keeping in mind that this model has been trained on tonnes of objects. For a better accuracy it will be a pretty good idea 
to train a model on target objects instead of 1000's of objects.
