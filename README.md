# Artificial Intelligence with TensorFlow <img alt="packt" src="https://i.imgur.com/ZyhGUP8.jpg" width="50" align="right">

Upcoming Packt video course, taught by Brandon McKinzie. The purpose of the course is to provide users with a comprehensive overview of what [TensorFlow](https://www.tensorflow.org) has to offer.

Here you will find all code used throughout the course, grouped by section. To learn more about the contents of any subdirectory, click its link in the table of contents below.

## Table of Contents

* [section1](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section1): **TensorFlow and Machine Learning Fundamentals**.
* [section2](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section2): **Computer Vision**.
* [section3](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section3): **Natural Language Processing and Recurrent Neural Networks**.
* [section4](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section4): **Tips and Tricks**.
* [section5](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section5): **TensorFlow in Production**. Also solely responsible for:
  - `tools` directory containing a bazelrc file.
  - `workspace.bzl` containing the `tensorflow_http_archive` function that allows us to import tensorflow via Bazel.
  - `WORKSPACE`: standard Bazel WORKSPACE file for import TensorFlow and any dependencies.
* [section6](https://github.com/mckinziebrandon/ai-with-tensorflow/tree/master/section6): **Miscellaneous Topics and Course Summary**. Contains `eager.py` from video 6.3 on TensorFlow Eager. (No other video in section 6 had code)

## Getting Setup

1. [Install TensorFlow](https://www.tensorflow.org/install) for Python 3.
2. Download data into the `data` directory from the [shared Google Drive](https://drive.google.com/drive/folders/1F48AxX_6C_-1MpQz5pYyqELiHzmpRKvA?usp=sharing)


## TODO

- probably should move all bazel stuff into section5
- go through each section and delete any file that wasn't in a video
- add documentation to everything