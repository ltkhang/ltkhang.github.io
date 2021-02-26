---
layout: post
title: Verify deep face recognition pretrained models on Asian faces datasets (CASIAFaceV5 and Asian face dataset-AFD)
---

This is a part of my project which aims to verify the accuracy of some current face recognition pretrained models (ArcFace) on Asian faces datasets.

I was using CASIA-FaceV5 and AFD dataset. In overall, all of tested models achieved really high accuracy (over 99%). Therefore, I decide to use Mobilefacenet model to apply to
light-weight face tracking and recognition in another post.

Guide to setup is shown in github project:

CASIAv5
```
https://github.com/ltkhang/CASIA_FACE_V5_verification
```

AFD

```
https://github.com/ltkhang/CASIA_FACE_V5_verification/tree/master/AFD_Images_verification
```

To use this project as a part of your works, please make sure you cite all the related ones:

CASIA FACE V5

```
http://www.idealtest.org/dbDetailForUser.do?id=9
```

ARCFACE

```
@inproceedings{deng2018arcface,
title={ArcFace: Additive Angular Margin Loss for Deep Face Recognition},
author={Deng, Jiankang and Guo, Jia and Niannan, Xue and Zafeiriou, Stefanos},
booktitle={CVPR},
year={2019}
}
```

Any trouble in set up, feel free to open issue or contact me via email.


