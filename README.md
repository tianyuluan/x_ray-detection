**x_ray-detection 科大讯飞**
机场，车站等场所安检机器产生的x光安检图像，设计算法对其进行违禁品检测，类别：knife、scissors、lighter、zippooil、pressure、slingshot、handcuffs、nailpolish、powerbank、firecrackers。
**框架：**
mmdetection 配置安装：https://github.com/open-mmlab/mmdetection/blob/master/docs/get_started.md
**整体结构**：
Detectors+OHEM+Soft_NMS+Mixup
**训练策略**：
多尺度训练+多尺度预测
