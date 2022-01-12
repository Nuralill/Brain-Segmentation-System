## AD_Prediction
毕业设计项目-基于深度学习的阿兹海默症早期诊断辅助系统设计与实现
## 系统启动说明
  1，打开Pycharm，导入该项目，并安装Tensorflow、keras、Flask等需要的包（命令行安装）；
	2，运行项目下的ADMS/app.py文件，运行成功后，会出现一个URL，点击或复制到浏览器中打开，并可自动跳转到系统登录首页。
	3，ADMS下的两个h5文件放置的是训练好的模型，需要进行联合预测的两种模型
	4，ADMS/Unet3d文件夹：
		放置的是辅助预测算法部分代码，其中的brats文件夹下是主要部分，通过allSteps来调用
    ADMS/Unet3d/data文件夹：
    放置了输入输出数据
	5，static文件夹：
		放置的是Web系统所需要的css、js以及用户上传图像、预测图像以及上传的诊断结果保存目录
	6，templates文件夹：
		放置的是Web系统的前端HTML页面

基于3dunet的大脑图像分割系统
