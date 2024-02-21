# fallDetectorWithOpenPose
Project made in python. The purpose of this project is to detect fall with an Knn-Algorithm. To do so was created a dataset with the values of the position and angle of the body and used to classify  a movement between fall and not fall. It was used 2 ways of classification, one considering just a single frame and other considering a set of frames.

Applying the Knn algorithm considering each single frame, the project was able to detect fall, but its acurracy wasn't perfect, as shown on the figure, where 0 is falling and 1 is not falling.
![alt text](https://github.com/JoViGaCa/fallDetectorWithOpenPose/blob/main/images/matrixAnalisysFrame.png)

Applying the Knn algorithm considring a set of frames, the project was able to detect fall, but its acurracy wasn't perfect, as shown on the figure, where 0 is falling and 1 is not falling.
![alt text](https://github.com/JoViGaCa/fallDetectorWithOpenPose/blob/main/images/matrixAnalisysSet.png)

In conclusion, the project made possible to detect fall:
![alt text](https://github.com/JoViGaCa/fallDetectorWithOpenPose/blob/main/images/bodyFalling.png)

And "not fall":
![alt text](https://github.com/JoViGaCa/fallDetectorWithOpenPose/blob/main/images/bodyNotFalling.png)
