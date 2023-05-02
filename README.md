# 交通科技创新竞赛实验题目

## 要求：
1. 车辆检测，保存识别结果

自行拍一段30s左右的视频，将识别结果存成 txt，csv 或其他格式 ，对于视频每一帧图像 包括：当前帧数（第几帧），每一个目标：类别，置信度，boundingbox 对角点坐标 （左上与右下角点坐标），用于后续分析。

2. 车辆统计，自定义分析目标


以下是往届自定义目标的示例：
- 统计当前帧每个车道车辆数，并实时显示。（拉取四边形代表某条车道范 围，判断该四边形内有多少各目标。）
- 统计每条车道累计车辆数。（划定虚拟检测线 or 线圈，经过则计数。）
- 
3. 进一步讨论


根据检测结果与目标，再实现过程中进一步分析。（如讨论交通量、光照、遮挡，使用的算法等影响因素对结果的影响，该部分同样纳入作业评定中。）

## 提交形式

/src：可执行的源代码

/video：原始视频和识别后的视频

/output：识别结果文件

/report：分析报告（实验目标、方法、结果、讨论、参考）
  
## YOLO_v3_tutorial_from_scratch
Accompanying code for Paperspace tutorial series ["How to Implement YOLO v3 Object Detector from Scratch"](https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/)

Here's what a typical output of the detector will look like ;)

![Detection Example](https://i.imgur.com/m2jwnen.png)

## About the training Code

This code is only mean't as a companion to the tutorial series and won't be updated. If you want to have a look at the ever updating YOLO v3 code, go to my other repo at https://github.com/ayooshkathuria/pytorch-yolo-v3

Also, the other repo offers a lot of customisation options, which are not present in this repo for making tutorial easier to follow. (Don't wanna confuse the shit out readers, do we?)

About when is the training code coming? I have my undergraduate thesis this May, and will be busy. So, you might have to wait for a till the second part of May. 

Cheers

