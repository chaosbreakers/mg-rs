# mg-rs

## Image Recognition

### 目标
* 建筑物识别
* 建筑物分类
* 估计各类建筑面积

### 已标记数据
* [ISPRS benchmarks](http://www2.isprs.org/commissions/comm3/wg4/tests.html)
* [SpaceNet](https://aws.amazon.com/public-datasets/spacenet)
* [OSM (OpenStreetMap)](https://github.com/developmentseed/skynet-data)

### 方法

#### faster RCNN

https://github.com/ShaoqingRen/faster_rcnn

#### SegNet

https://github.com/developmentseed/spacenet-data
https://github.com/developmentseed/skynet-train

#### SegNet with features
1. 复现 [DeepNetsForEO](https://github.com/nshaud/DeepNetsForEO) 中的工作，暂不考虑对比6通道融合模型，分别复现并单独测试两种3通道模型（DSM-NDSM-NDVI&IR-R-G）的结果。
2. 将 SpaceNet 的数据配置成（DSM-NDSM-NDVI）格式，并进行测试。

### 资料

https://code.facebook.com/posts/561187904071636
https://devblogs.nvidia.com/parallelforall/exploring-spacenet-dataset-using-digits/
