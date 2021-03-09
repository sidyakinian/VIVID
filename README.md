# VIVID

This is a side project that I worked on in March-April 2019 in collaboration with a friend. He was working on the server side, while I was doing UI/UX.

## Description

VIVID is (an unfinished) iOS app that transforms sketches into landscapes using machine learning. It uses an ML model from NVIDIA called SPADE (Semantic Image Synthesis with **Sp**atially-**A**daptive (**De**)Normalization, [GitHub](https://github.com/NVlabs/SPADE), [paper](https://arxiv.org/abs/1903.07291)). NVIDIA didn't publicly release the code for the pre-trained model, only the code for training; however, by our initiative, we collaborated with several programmers and AI researchers and trained the model together ([GitHub thread](https://github.com/NVlabs/SPADE/issues/17), [a Tweet by one of the collaborators](https://twitter.com/genekogan/status/1136263149412335616) about this effort).

Here's [a demo video](https://www.youtube.com/watch?v=MXWm6w4E5q0&t=67s) of the pre-trained model by NVIDIA. Also, two GIFs showing how the model transforms sketches into landscape pictures:

![ocean](https://user-images.githubusercontent.com/34050187/110402417-391e3a80-8030-11eb-910d-b76225881675.gif)
![treepond](https://user-images.githubusercontent.com/34050187/110402427-3ae7fe00-8030-11eb-9449-0879ae9c378a.gif)

## iOS app demo

Here are some demo videos of the app.

Drawing on canvas:

![canvas](https://user-images.githubusercontent.com/34050187/110403759-826f8980-8032-11eb-8e50-fe2ddc39b95c.gif)

Sending http request to server to transform the sketch (the servers were off when this recording was taken, so it doesn't show the transformation, just the UI):

![loading](https://user-images.githubusercontent.com/34050187/110403760-83082000-8032-11eb-9008-fd7dbbf62947.gif)

Settings ViewController:

![settings](https://user-images.githubusercontent.com/34050187/110403756-7f749900-8032-11eb-8bac-167c46f7aead.gif)
