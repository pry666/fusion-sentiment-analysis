# fusion-sentiment-analysis
## 1.requirements.txt
为代码所需环境

## 2.代码文件结构
```
|-- 实验五数据/
    |-- data/ #由于数据太多传不上就建了个1.txt作为样例
        |-- 1.txt
    |-- train.txt
    |-- test_without_label.txt
|-- p5.ipynb # 在这里面运行每个单元格即可
|-- test_with_label.txt #测试结果
|-- 实验五数据.zip #因为大于25MB所以无法上传，运行时需要该zip文件
```

## 3.代码执行流程
运行p5.ipynb中的每个单元格即可（需要在google colab上运行）\
本地运行时则从一下单元格开始运行即可
```
import transformers
import pandas as pd
import torch
```


## 4.参考库
https://github.com/huggingface/transformers\
使用的预训练模型bert为trainsformers中的，resnet101则在torchvison包中
