# DeepLearningRoadIdentification

This project presents our solution for the traffic environment task where the objective is to train a model using images captured by six different cameras attached to the same car to generate a top down view of the surrounding area for road map layout and object detection. For this task we use a simple framework for contrastive learning of visual representations(SimCLR) along with self supervised Monocular Depth estimation on the upstream task. Then we use these learned representations for our downstream tasks using state of the art model for Road Prediction like DeepLab and Object Detection using Faster RCNN to achieve our goal.

## Tasks:

![Road Map Accuracy](images/Task.png)


## Architecture:


## Results:
Baseline:

LAG - 1 - Bounding Box Score: 0.01438 - Road Map Score: 0.704

Final:
LAG - 1 - Bounding Box Score: 0.017 - Road Map Score: 0.73

## Testing Results:

![Road Map Accuracy](images/Result_Road_map.png)

![Road Map Accuracy](images/object%20detection.png)

# Outputs:

![Road Map Accuracy](/images/OriginalImage.jpg)

![Road Map Accuracy](images/DepthImage.jpg)

## Team Name:
+ Team Name: LAG \
+ Team members : Sree Gowri Addepalli (sga297@nyu.edu) \
             : Amartya Prasad (ap5891@nyu.edu)    \          
             : Sree Lakshmi Addepalli(sla410@nyu.edu) \






