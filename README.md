# 简介
本数据集为目前已知最大的人像matting数据集，包含34427张图像和对应的matting结果图。  
数据集由北京玩星汇聚科技有限公司高质量标注，使用该数据集所训练的人像软分割模型已商用。  
数据集中的原始图片来源于Flickr、百度、淘宝。经过人脸检测和区域裁剪后生成了600*800的半身人像。  
clip_img目录为半身人像图像，格式为jpg；matting目录为对应的matting文件（方便确认matting质量），格式为png，您训练前应该先从png图像提取alpha图。例如使用opencv可以这样获得alpha图：  
in_image = cv2.imread('png图像文件路径', cv2.IMREAD_UNCHANGED)  
alpha = in_image[:,:,3]  
  
# 下载地址
链接：https://pan.baidu.com/s/1R9PJJRT-KjSxh-2-3wCGxQ 
提取码：dzsn 

  
# 数据集截图
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/1.png)  
  matting图：  
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/2.png)
  
# 更多数据
我们与阿里云市场联合推出的人像分割开放接口拥有数百家客户，每天处理数十万张照片，积累了海量的数据。  
如果您需要更多训练数据，请与我们联系。  

# 合作
我们的目标是打造中国版remove.bg！  
我们欢迎高校的图像语义分割、视频语义分割的研究者与我们开展合作，我们可以提供海量的数据和真实的客户需求。  
公司官网：www.aisegment.com ，可体验语义分割效果。  
算法总监的联系方式：  
![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/3.png)
