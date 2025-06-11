
# 目标检测
## 红外目标检测
### SAMamba
+ 将SAM2的层级特征学习与Mamba的选择性序列建模相结合
+ https://github.com/zhengshuchen/SAMamba
+ https://zhuanlan.zhihu.com/p/1911831924307125278
### SDS-Net
+ 代码未发布，单红外图像，深浅特征融合，分割
+ https://zhuanlan.zhihu.com/p/1915457270755627204
+ https://github.com/PhysiLearn/SDS-Net



## 小目标检测
### Cross-DINO
+ 小目标检测，改进DETR,代码暂未开源
+ https://github.com/Med-Process/Cross-DINO
### ESOD
+ 小目标检测，传统方法改进yolo的候选区域提取，大输入尺度下的重型模型的小目标检测
+ 两块v100上，148GFLOPS，32.8fps
+ https://github.com/alibaba/esod
### FBRT-YOLO
+ 航空图像小目标检测、替换了骨干的C2f为FCM，添加了MKP,只用了p2、p3两层、轻量化、各大无人机数据集上精度均低于50
+ https://github.com/galaxy-oss/FCM
+ https://mp.weixin.qq.com/s/dAGXzEizorxkoTaxjg6uVw

## 超分辨率
### ms_sr_var
+ 代码未公开，transformer架构，参数量仅300M，AR_base（gan_base、diffusion_base）
+ https://zhuanlan.zhihu.com/p/1914358985231926361
+ https://github.com/saic-fi/ms_sr_var
### TADiSR
+ 代码未公开，文本图像超分辨率，扩散模型+文本感知注意力+联合分割解码器
+ https://github.com/mingcv/TADiSR
+ https://zhuanlan.zhihu.com/p/1914358985231926361
### DOVE
+ 视频超分辨率，基于diffusion，
+ https://github.com/zhengchen1999/DOVE
+ https://zhuanlan.zhihu.com/p/1909298854324598637

## 少样本异常检测
### UniVAD
+ 正常样本作为参考，免训练异常检测
+ https://github.com/FantasticGNU/UniVAD

## 密集人群计数
+ 代码暂未开源
+ https://github.com/Elin24/P2RLoss

## 图像复原
### BaryIR
+ 代码暂未开源
+ https://github.com/xl-tang3/BaryIR
### RestoreVAR
+ 代码未开源，基于transformer，比diffusion快10倍，达到0.2s左右
+ https://github.com/sudraj2002/RestoreVAR
+ https://zhuanlan.zhihu.com/p/1910384827695334970
### MODEM
+ 代码未开源，去雨去雾去雪，基于Morton序退化估计机制
+ https://github.com/hainuo-wang/MODEM
+ https://zhuanlan.zhihu.com/p/1910384827695334970
### ClearNight
+ 代码未公开，夜间复杂天气复原
+ https://github.com/henlyta/ClearNight
+ https://zhuanlan.zhihu.com/p/1909298854324598637


## 图像分类
### H2Crop
+ 高光谱农作物分类，基于transformer，自建数据集
+ https://github.com/flyakon/H2Crop
+ https://zhuanlan.zhihu.com/p/1915457270755627204

## 注意力机制
### PST
+ 即插即用、轻量化、添加到yolo颈部的每一个concat后面
+ https://github.com/inlmouse/PyramidSparseTransformer

## 知识蒸馏
### DeepKD
+ https://zhuanlan.zhihu.com/p/1908931981250651465
+ https://github.com/haiduo/DeepKD

## 图像上色
### powerful-attention
+ 基于扩散模型，5.2s推理时间
+ https://zhuanlan.zhihu.com/p/1908931981250651465
+ https://github.com/satoshi-kosugi/powerful-attention
