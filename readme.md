##  Image Recognition ARDrone Program

This project uses my other project SiegDrone.py for a backbone.

The added features for thie repository is a fully trained CNN using the CIFAR 10 imageset, and trained with CAFFE.

Standard connection to the drone, with controls setup for a PS4 controller.

New feature is the aiming square on the video feed.  Aim at your desired object and press the "O" circle button to
see if the image is recognized as a deer.  Code can be chaged to focus on the other 9 images that CIFAR was trained
with, so it can be adapted to the user.  Modifiable code resides in the SiegDrone.py file.
