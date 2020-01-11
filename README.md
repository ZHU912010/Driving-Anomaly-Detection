# Driving-Anomaly-Detection

For analyzing the traffic anomaly within dashcam videos in the perspective of ego-vehicle, the agent should spatial-temporally localize the abnormal occasion and regions and give a semantically recounting of what happened. Most existing formulations concentrate on the former spatial-temporal aspect and mainly approach this goal by training normal pattern classifiers/regressors/dictionaries with large-scale availably labeled data. However, anomaly is context-related, and difficult to distinguish the margin of abnormal and normal clearly. This paper proposes a progressive unsupervised driving anomaly detection and recounting (D&R) framework. The highlights are three-fold. 1) We formulate driving anomaly D&R as a temporal-spatial-semantic (TSS) model, which achieves a coarse-to-fine focusing and generates convincing driving anomaly D\&R. 2) This work contributes an unsupervised D&R without any training data while performing an effective performance. 3) We novelly introduce the traffic saliency, isolation forest, visual semantic causal relations of driving scene to effectively construct the TSS model. Extensive experiments on a driving anomaly dataset with 106 video clips (temporal-spatial-semantically labeled carefully by ourselves) demonstrate superior performance over existing techniques.

The pipeline of this work. ![image](https://github.com/ZHU912010/Driving-Anomaly-Detection/blob/master/The%20TSS%20module.png)

The Drive-Anomaly106 dataset, Groundtruth and our results can be downloaded [Here](https://pan.baidu.com/s/1EBQdRYJXyAiTaP_zPry8wQ).

This dataset proposed in paper [Vehicle re-identification in tunnel scenes via synergistically cascade forests](https://doi.org/10.1016/j.neucom.2019.11.069)

This dataset proposed in paper [Progressive Temporal-Spatial-Semantic Analysis of Driving Anomaly Detection and Recounting](https://doi.org/10.3390/s19235098)
