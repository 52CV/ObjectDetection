# Object Detection

## 1.EfficientDet

### [EfficientDet: Scalable and Efficient Object Detection](https://arxiv.org/abs/1911.09070)

EfficientDet 是谷歌大脑团队在2020年3月发布的一个目标检测模型。与之前的检测器如 Mask R-CNN 相比，它以更少的参数和 FLOPs 达到了最先进的 53.7%COCO 平均精度（AP）。有 8 种变体，从 D0 到 D7，尺寸和精度都在不断改进。此外，最近发布了一个超大版本 D7x，达到 55.1% 的 AP。

- CVPR 2020
- [Github](https://github.com/google/automl/tree/master/efficientdet)

## 2.YOLO 系列

### [YOLO 系目标检测算法家族全景图！](https://mp.weixin.qq.com/s/wjUiSRcP49gkn5YwpPyPpA)

### [Scaled-YOLOv4: Scaling Cross Stage Partial Network](https://arxiv.org/2011.08036)

YOLOv4-large 在COCO数据集达到SOTA精度: 55.4% AP(73.3% AP50) 并以以15 fps 在 Tesla V100运行, 而如果加上测试阶段数据增强方法后,YOLOv4-large 达到 55.8% AP (73.2 AP50). 作者称这一精度是所有已公开文献的最高精度.
   
   - [上达最高精度，下到最快速度，Scaled-YOLOv4：模型缩放显神威](https://mp.weixin.qq.com/s/Uo5pge7uq-Bh_wR9Vd5M7w)
   - [Github](https://github.com/WongKinYiu/ScaledYOLOv4)
   
   ## 3.NanoDet
   
  ### [NanoDet：轻量级（1.8MB）、超快速（移动端97fps）目标检测项目](https://mp.weixin.qq.com/s/KC-QxYZf2471OICDFra7Zw)
   
  ### [YOLO之外的另一选择，手机端97FPS的Anchor-Free目标检测模型NanoDet现已开源~](https://mp.weixin.qq.com/s/7mHhltqDcnYZdHWoRS_EBg)
   
   - 1.8MB超轻量，跑的比 YOLO 快
   - [Github](https://github.com/RangiLyu/nanodet)


# Salient Object Detection (SOD)

## 1.U^2-Net

### [U2-Net: Going Deeper with Nested U-Structure for Salient Object Detection](https://arxiv.org/abs/2005.09007)

- ICPR 2020
- [Github](https://github.com/NathanUA/U-2-Net)

## 2.BASNet

### [BASNet: Boundary-Aware Salient Object Detection](https://openaccess.thecvf.com/content_CVPR_2019/html/Qin_BASNet_Boundary-Aware_Salient_Object_Detection_CVPR_2019_paper.html)

- 在单个GPU上的运行速度超过25 fps
- CVPR 2019
- [Github](https://github.com/NathanUA/BASNet)
