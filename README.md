# DeepLearningRoadIdentification

This is the repository for Yann Le cunn project:


Baseline:

LAG - 1 - Bounding Box Score: 0.01438 - Road Map Score: 0.704

Final:
LAG - 1 - Bounding Box Score: 0.017 - Road Map Score: 0.73





FRRNB - large model

Self Supervision (SIMCLR) + Deep Lab (Downstream) RoadMap: - 0.65
Self Supervision (SIMCLR + Monocular) + Linear RoadMap: - 0.62 - 0.68 (Few epochs training, overfit)

Self Supervision (SIMCLR) + Faster RCNN (Downstream) object Detection: - (PIL image, cant take more than 3 channels)
Self Supervision (SIMCLR + Monocular) + Faster RCNN object Detection: 

Self Supervision (SIMCLR + Monocular) + Linear object Detection: 

Self Supervision (Monocular + Faster RCNN) object Detection -)

Self Supervised - MonoLayout - Failed ( Top Down view  accuracy bad) (6 supervised models)
Self Supervised - Pseudo Lidar - Failed (https://piazza.com/class/k5spqaanqk51ks?cid=319)

Developed our loss function to minimize over IoU - directly optimise iouloss, giou

RetinaNet




