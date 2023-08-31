#基于yolov8和Transformer的车牌识别
##1.使用最先进的yolov8-pose作为目标检测器；在检测车牌bbox的同时获得关键点来透视变换，以应对角度旋转问题！
##2.使用独创的Tripartite Architecture，将车牌解构为（省份---拉丁字符主体---后缀）三个部分，从而解决省份识别率低的问题！
##3.使用高效的Transformer做车牌特征的提取，与RNN不同，并未将车牌视为从左到右的单行序列，因此对于双行车牌的识别准确度非常高！
文章名Tripartite Architecture License Plate Recognition based on Transformer 即将被PRCV2023接收。
![image](https://github.com/xiamangfu/Chinese-License-Plate-Transformer/assets/93989306/30b0d4e6-d331-44cb-a4c0-fb144543444b)
![Uploading image.png…]()
