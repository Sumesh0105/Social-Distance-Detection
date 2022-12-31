# Social-Distance-Detection


In the fight against the corona virus, social distancing is very important and effective measure to slow down the spread of the disease. Many peoples in the industries are still affected by corona virus.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection tool that can detect people who are not keeping a safe distance from each other by analyzing the recorded video streams from the camera.


First it detects the humans in the frame with yolov3 convolutional neural network.
Then it calculates the distance between all the instances of humans detected in the frame.
At last Social distancing violations are displayed in the video stream.

# OUTPUT
![Screenshot_20221231_214708](https://user-images.githubusercontent.com/113231945/210149475-3726c311-002d-40d8-ad48-3a93e5c9723e.png)


Download yolov3.weights for COCO dataset from https://pjreddie.com/darknet/yolo/
