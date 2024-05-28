# ResNet-LSTM 针尖刺入图片序列分类

本项目仅仅提供了最基础的ResNet-LSTM分类模型，代码是作者在学习机器视觉课程时写的，对于初学者还算比较好理解，细节上有不足的地方，大家可以自行修改。读者在使用的时候有任何问题和建议都可以通过邮件联系我。

## 数据描述

数据集文件夹injection-dataset_student包含两个子文件夹injSuccess和injFail，每个子文件夹内有40个图片序列，每个序列由8张图片组成。

我人为地将原文件夹按8:2分为injection-dataset_train和injection-dataset_test，分别用于模型的训练和测试。

## 模型讲解

ResNet-LSTM是先由ResNet预训练模型提取图片特征，之后利用LSTM来处理序列图像的一种深度学习网络构建方法。