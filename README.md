# Intention prediction 

An introduction to intention prediction scenario and data set.


## Experiment scenario

<p align="center">
<img width="450"  src="https://github.com/fantasylsc/Intention_Prediction/blob/master/images/Experiment.PNG" >
</p>

The experiment is about a human participant pitching a ball toward a robot (represented by a target area in the figure). The target area is divided into 9 grids which represent the 9 targets that the ball can hit. We expect the robot to be able to predict the intention of the participant (i.e., which of the nine targets the participant is pitching the ball to). 




## Data set

A data set of human intentions behind human actions. This data set is built from multiple human priticipants. The dataset contains RGB images, RGB-D images, and skeleton data of human actions.

The data set is free to use for non-commercial purposes.



- RGB images: [RGB-part1](https://pan.baidu.com/s/1qX14X9l2fYqx3DCZS0lwpw) [RGB-part2](https://pan.baidu.com/s/1LahYjJ32j6MkdBhk3Beksw) [RGB-part3](https://pan.baidu.com/s/1wHbBykIZuv-rydh02fyXnA) [RGB-part4](https://pan.baidu.com/s/1q9XqCx-fe--usnkd9Bc1lA) [RGB-part5](https://pan.baidu.com/s/1Qvyt94w2WGKpliqAdjlK6Q)

- RGB-D images: [RGB-D-part1](https://pan.baidu.com/s/127n2swlXOplj88i2Lftsgw) [RGB-D-part2](https://pan.baidu.com/s/11Uu4VjhXyxVBYFT_Hioeng) [RGB-D-part3](https://pan.baidu.com/s/1-9GmlgnGm1zJ7VtjWpbKUg)

- Skeleton data: [Skeleton](https://pan.baidu.com/s/1_k7hUam23iLRsU0ID8bldQ)

If this data set is useful for your research, please refer to our paper: 

Shengchao Li, Lin Zhang, and Xiumin Diao - [Improving Human Intention Prediction Using Data Augmentation](https://ieeexplore.ieee.org/document/8525781/keywords#keywords)
  ([BibTeX](https://github.com/fantasylsc/Intention_Prediction/blob/master/Bib/LiZD18.bib))

## Others
1. data_acquire: capture 3 sec video by Kinect V2 under Matlab and save the data.

2. dataset_utils:
- `travaltes_slicing.py` slices dataset to train/validation/test by proportion of 6/2/2.
- `create_pitch_tf_record.py` create tfrecord shards.

3. `pitch2d_main.py` training and evaluation.
