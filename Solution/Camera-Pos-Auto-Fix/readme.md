# 传感器抖动自动纠偏
不论是 v2x 中架设在路口杆上的摄像机还是 车端的相机组，都可能存在相对位置的改变，这会引发相机外参的变化，导致像素空间到 bev 空间的映射计算出现误差，尤其是远端的目标，这种误差会得到极大的放大。

