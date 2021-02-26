---
layout: post
title: Face recogntion on Jetson nano.
---

This is my internship project of TEEP at National Chung Cheng University, Taiwan. This work aims to build a MVP version of light-weight face recogntion to deploy on resource-constraint
devices such as Raspberry Pi, Jetson nano. The main device in this project is Jetson nano, I have not tetsed on Rasperry Pi. If you have done that, feel free to share with me,
I will update on this post.

About technical problems. I used YoloV4-tiny for face detection [here](https://ltkhang.github.io/face-detection-yolov4-tiny/) which achieved about 25-30fps on Jetson nano.
Secondly, aim to improve the accuracy of face identification on Taiwanese faces, therefore, I tested some pretrained models of deep face representation (ArcFace) on 2 Asian
faces datasets. This work is represented [here](https://ltkhang.github.io/verify-deep-face-recognition-on-asian-face-dataset/).
Finally, after combine above 2 works and [SORT] (https://github.com/abewley/sort) algorithm, I produced a MVP face recogntion system on Jetson nano which you can refer to build, to improve or to integrate on your system.
I used SORT algorithm for reducing face recognition time. Because I could achieve about 25fps on face detection, however I could only achieve that of face recognition about 20 faces/minute.

Code for this project is on the repo:

```
https://github.com/ltkhang/ccu-mvp-face-recognition
```

Demo video on Jetson nano:

[![](http://img.youtube.com/vi/grARFiksUik/0.jpg)](http://www.youtube.com/watch?v=grARFiksUik "")


Any trouble in set up, feel free to open issue or contact me via email.

