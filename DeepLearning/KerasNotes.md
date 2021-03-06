# Keras 学习笔记
## 环境配置  
 为了简单，在Anaconda下完成keras开发环境的配置。Anaconda的安装见安装教程。
 由于Keras兼容的Python版本为2.7-3.6，因此需要专门配置python3.6的环境。

```bash
$conda create --name py36 python=3.6
$conda activate py36 #进入Python 3.6环境
$conda install tensorflow #安装TensorFlow
$conda install keras #安装Keras
```
可以使用cifar10例子在jupyter中进行测试
[相关代码在Keras文档](https://keras.io/preprocessing/sequence/)中。  
知乎上关于[Keras的配置教程](https://zhuanlan.zhihu.com/p/36551413)

## 关于模型传递
[Keras模型转为ONNX](https://xadupre.github.io/keras-onnx/index.html)  
可以实现训练模型与matlab平台的兼容处理。

