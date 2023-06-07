# cv3-mobilevit
1.根据论文中网络架构及实现细节，搭建自己的MobileViT模型，代码已经在仓库\
2.下载并组织好数据集，更改相关路径信息，直接在官网下载数据集即可本次实验使用UCMerced_LandUse\
3.加载预训练权重，本实验所采用的是官方开源的mobilevit_xxs.pt\
4.进行模型训练，在训练过程中，保存训练过程中效果最好的一组权重，用于后续测试环节\
5.对训练得到的效果最好的模型进行测试

对应文件夹架构：\
├─images：可传入一些测试图片\
├─runs\
│  ├─Jun02_16-58-10_YiYue\
│  ├─Jun02_17-00-38_YiYue\
│  ├─Jun02_17-29-06_YiYue\
│  ├─Jun02_17-32-26_YiYue\
│  └─Jun02_17-33-32_YiYue\
├─UCMerced_LandUse\
│  ├─agricultural\
...\
│  └─tenniscourt\
├─weights：本机训练后保存的权重\
└─__pycache__

参考链接：\
MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer：https://arxiv.org/abs/2110.02178 \
代码参考：\
https://github.com/WZMIAOMIAO/deep-learning-for-image-processing/tree/master/pytorch_classification/MobileViT \
https://github.com/apple/ml-cvnets \
https://github.com/huggingface/pytorch-image-models
