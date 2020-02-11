# Random-Python-Scripts
Scripts written on free time and when found new learnings

# C++ Tutorial
https://classroom.udacity.com/courses/ud210

# Tensorflow Tutorials
https://github.com/aymericdamien/TensorFlow-Examples
https://github.com/MorvanZhou/Tensorflow-Tutorial

# All ML and DL
https://github.com/lazyprogrammer/facial-expression-recognition

# OpenCV

# Colab files
a. Detectron2
https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5#scrollTo=9_FzH13EjseR

# extract frames from video
ffmpeg -ss 60 -i input.mp4 -qscale:v 4 -frames:v 1 output.jpg
# rename files in linux
c=0 rename  's/.*/sprintf("marksheet%d.jpg", ++$ENV{c})/e' *
# change image orientation
exiftran -ai *.JPG

#How to embed the video url in the markdown.
* Used http://embedyoutube.org/ . Provide the youtube url and this website will generate the embed url, which can be used in the markdown.

# Add github file in colab
# import clr file from github
# Fetch a single <1MB file using the raw GitHub URL.
!curl --remote-name \
     -H 'Accept: application/vnd.github.v3.raw' \
     --location https://raw.githubusercontent.com/BalajiB197/EIP2/master/keraslearningrate/clr_callback.py

