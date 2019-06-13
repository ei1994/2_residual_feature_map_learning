## 2、residual_feature_map_learning

## train_nature_map32_X.py：训练和测试的代码；model_d_map32_X：模型的代码
diff_res: 特征残差累积学习网络结构（参数共享）    
diff_res_pro: 三次度量网络（参数共享）

## 简介：
基于特征残差学习的异源图像块匹配方法。通过对基于特征图差值融合方法的分析发现，差异特征信息在图像匹配中十分重要。针对图像的高层残差特征中会缺失重要细节信息的问题，通过增加副分支卷积网络的方式，对主干网络中不同卷积层得到的多个尺度残差特征图组进行特征学习。该策略将底层的细节残差特征与高层的语义残差特征进行结合，充分挖掘图像中有利于匹配的重要特征信息。在此基础上，本文进一步将主干网络与副分支网络得到的高层残差特征进行组合学习，利用三次度量的方式来提高匹配预测的准确率和泛化性能。

Second, heterogeneous image patches matching method based on residual feature map learning. Through the analysis of the feature map fusion method based on their difference, it is found that the information on the difference features is very important in image matching. Aiming at the problem that some important detail information is missing in the high-level residual feature maps, the learning of multiple scale residual feature maps obtained from different convolutional layers in the backbone network is performed by adding a sub-branch convolution network. The strategy integrates the underlying detail residual features and the high-level semantic residual features to fully exploit the key feature information in the image, which is instrumental in image patches matching. On this basis, this paper further combines the high-level residual feature maps obtained from the backbone network and the sub-branch network, and uses the three-measurement method to improve the accuracy and generalization performance of the matching.
