# GazeDirection_BinaryClassification

The dataset presents the gaze of different people, whose idea and motivation is to be able to create a model that accurately indicates whether the person is looking straight ahead (at the camera lens) or not.

The dataset (https://www.kaggle.com/datasets/estopadilla/gaze-direction-detection) contains one numpy file with 53k entries, divided into right eye, left eye and target (the last one representing in binary form whether the person is looking straight ahead or not). The shape is:

- Right eyes shape: (53000, 64, 64, 3)
- Left eyes shape: (53000, 64, 64, 3)
- Targets: (53000, 1)

For this test, all test are performed using CNN from scratch and pretrained weights with MobileNetV2.