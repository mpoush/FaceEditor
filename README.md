# Face Editor
Unsupervised learning to find facial features.
https://youtu.be/4VAkrUNLKSo

The main order is:

1. edit `datagen.py` to point to the correct directory, etc.
2. run `python datagen.py`
  * (this creates a bunch of training data)
3. run `python encoder.py`
  * This starts modeling the data, and periodically saves off evaluation summaries as well as the all-important `Encoder.h5`
4. Once you have an `Encoder.h5`, run `face_edit.py` to see the result of applying different dimensions.
