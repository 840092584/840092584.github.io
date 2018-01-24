### Abstract

Tracking multiple people in crowds is a fundamental and essential task in the multimedia field, and it is often hindered by difficulties
such as dynamic occlusion between objects, cluttered background and abrupt illumination changes. In this paper, we joint deep and depth 
to propose a novel object-level segmentation strategy and stereo tracking method in crowds. More specifically, first we present a novel object-level segmentation strategy, which combines the results of deep learning detection method with the 3-dimensional information obtained by stereo vision algorithm to get precise segmentation results in the image. Thereafter, on the basis of precise segmentation results, we propose a novel stereo tracking method based on two-tier data association, which aiming at improving the performance of multiple object tracking in severe occlusion. Finally, we construct a real-time stereo tracking system and build a diverse stereo dataset, including a variety of real challenging indoor and outdoor scenes. The comprehensive experiments verify the effective and robust tracking performance of our approach in various crowded scenes. In addition, the qualitative and quantitative comparison results underline the superiority of the proposed algorithm over the tested state-of-the-art tracking approaches.

### Data

![Image](dataset.png)

Dataset and demo video can be downloaded [here](https://pan.baidu.com/s/1kWqemhx),Total in size = 2.37G. Data was caputred 30frames/s, 
and the resolution of each frame is 1011*512. Each frame has been calibrated, can be directly done binocular stereo matching.


### Performance

![Image](demo.png)

Demo video for Joint Visibility Segmentation and Two-tier Data Association for Stereo Tracking in Crowds can be download [here](https://pan.baidu.com/s/1kWqemhx).
