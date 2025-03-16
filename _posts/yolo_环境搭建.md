---
layout:       post
title:        "yolo 环境搭建"
author:       "VincentYoung"
header-style: text
catalog:      true
tags:
    - k230
---

## yolo 简介

![](../../img/k230/2025-03-16-20-40-08-image.png)

[YOLO](https://arxiv.org/abs/1506.02640)(You Only Look Once）是一种流行的[物体检测](https://www.ultralytics.com/glossary/object-detection)和[图像分割](https://www.ultralytics.com/glossary/image-segmentation)模型，由华盛顿大学的约瑟夫-雷德蒙（Joseph Redmon）和阿里-法哈迪（Ali Farhadi）开发。YOLO 于 2015 年推出，因其高速度和高精确度而迅速受到欢迎。

- 2016 年发布的[YOLOv2](https://arxiv.org/abs/1612.08242) 通过纳入批量归一化、锚框和维度集群改进了原始模型。

- 2018 年推出的[YOLOv3](https://arxiv.org/abs/1804.02767) 使用更高效的骨干网络、多锚和空间金字塔池进一步增强了模型的性能。

- [YOLOv4](https://arxiv.org/abs/2004.10934)于 2020 年发布，引入了 Mosaic[数据增强](https://www.ultralytics.com/glossary/data-augmentation)、新的无锚检测头和新的[损失函数](https://www.ultralytics.com/glossary/loss-function)等创新技术。

- [YOLOv5](https://github.com/ultralytics/yolov5)进一步提高了模型的性能，并增加了超参数优化、集成实验跟踪和自动导出为常用导出格式等新功能。

- [YOLOv6](https://github.com/meituan/YOLOv6)于 2022 年由[美团](https://www.meituan.com/)开源，目前已用于该公司的许多自主配送机器人。

- [YOLOv7](https://github.com/WongKinYiu/yolov7)增加了额外的任务，如 COCO 关键点数据集的姿势估计。

- [YOLOv8](https://github.com/ultralytics/ultralytics)Ultralytics YOLOv8 引入了新的功能和改进，以提高性能、灵活性和效率，支持全方位的视觉人工智能任务、

- [YOLOv9](https://docs.ultralytics.com/models/yolov9/)引入了可编程梯度信息 (PGI) 和广义高效层聚合网络 (GELAN) 等创新方法。

- [YOLOv10](https://docs.ultralytics.com/models/yolov10/)是由[清华大学](https://www.tsinghua.edu.cn/en/)的研究人员使用该软件包创建的。 [Ultralytics](https://www.ultralytics.com/)[Python 软件包](https://pypi.org/project/ultralytics/)创建的。该版本通过引入端到端头（End-to-End head），消除了非最大抑制（NMS）要求，实现了实时[目标检测](https://docs.ultralytics.com/tasks/detect/)的进步。

- **[YOLO11](https://docs.ultralytics.com/models/yolo11/)** 🚀**新消息**：Ultralytics 最新的YOLO 模型可在[物体检测](https://docs.ultralytics.com/tasks/detect/)、[分割](https://docs.ultralytics.com/tasks/segment/)、[姿态估计](https://docs.ultralytics.com/tasks/pose/)、[跟踪](https://docs.ultralytics.com/modes/track/)和[分类等](https://docs.ultralytics.com/tasks/classify/)多项任务中提供最先进的 (SOTA) 性能，充分利用了各种人工智能应用和领域的能力。

yolo 玩起来，谷歌在线笔记本，简介，运行yolo例子

## yolo 本地环境

yolo 项目托管平台，玩起来，本地训练模型，手机上

k230 模型训练基础，简介，模型框架

k230 yolo模型训练

模型部署和测试

扩展学习，yolo 教程，谷歌在线笔记本
