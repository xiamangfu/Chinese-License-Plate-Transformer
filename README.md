# -Transformer-CLPT
使用最先进的yolov8-pose作为目标检测器，可以使用Tripartite Architecture，将车牌解构为（省份---拉丁字符主体---后缀）三个部分，从而解决省份识别率低的问题！同时，Transformer与RNN不同，并未将车牌视为从左到右的单行序列，因此对于双行车牌的识别准确度非常高。
