# Pre-Trained Models for DeepFace

Pre-trained weights in deepface were stored in Google Drive source but it has a daily download limit. Users can get **"Too many users have viewed or downloaded this file recently. Please try accessing the file again later"** often. That's why, pre-trained weights are going to be stored in this repo as a release.

The repo itself is licensed under MIT - see [`LICENSE`](https://github.com/serengil/deepface_models/blob/main/LICENSE). However, the library wraps some face recognition models: [VGG-Face](http://www.robots.ox.ac.uk/~vgg/software/vgg_face/), [Facenet](https://github.com/davidsandberg/facenet/blob/master/LICENSE.md), [OpenFace](https://github.com/cmusatyalab/openface/blob/master/LICENSE), DeepID, [ArcFace](https://github.com/leondgarse/Keras_insightface/blob/master/LICENSE). Pre-trained weights of those models converted from original source to Keras, and they are going to be stored in this repo. So, licence types will be inherited if you are going to use those models.

Besides, age, gender, emotion and race prediction models were trained by the author on the [VGG-Face](http://www.robots.ox.ac.uk/~vgg/software/vgg_face/) structure. License type of VGG-Face inherited to those models as well.
