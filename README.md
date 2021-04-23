# ikatago FAQ

## 都有什么租机平台呢？

### 以下是暂时已知的租机平台，皆可将ikatago.ipynbs上传到juypter notebook使用：

[智星云](http://www.ai-galaxy.cn/)，直接在手机小程序选择ikatago镜像，输入用户名和密码后即可运行。  
[恒源智享云](https://gpushare.com/)，可选择在juypter内上传，或使用ikatago镜像，[教程](https://gpushare.com/docs/best_practices/ikatago/)在此。  
[极链云](https://cloud.videojj.com/)  
[mistgpu](https://mistgpu.com/)  
[Featurize](https://featurize.cn/)  
[矩池云](https://www.matpool.com/)  
[极客云](https://www.jikecloud.net/)  

### 以下是可上传文件的云电脑平台，可将群文件中的ikatago-server整合包上传到云桌面使用：

[顺网云电脑](https://cpc.icloud.cn/)  
[青椒云电脑](https://www.qingjiaocloud.com/)

## 权重类问题

### katago最强最新的40b权重可以在那里下载呢？

最新最强的权重可以在[katago分布式训练官网](katagotarining.org)下载，找到Strongest confidently-rated network字样，后面便是下载链接。  
例：Strongest confidently-rated network: [kata1-b40c256-s7660552704-d1858058038](https://media.katagotraining.org/uploaded/networks/models/kata1/kata1-b40c256-s7660552704-d1858058038.bin.gz)

### katago目前最强的60b权重在哪里下载呢？

[60b248号权重](https://media.katagotraining.org/uploaded/networks/models/kata1-extra/b60c320-s2480283136-d1813743898.bin.gz)

### 我有可能帮助到katago训练吗？

当然可以！我们很鼓励大家贡献自己的算力使katago更为强大！
事先准备：在[官网](katagotraining.org)注册一个账号，记得验证邮箱哦！  
如果是使用本机：在contribute_example.cfg修改用户名密码和想要同时跑的盘数，在命令行cd到katago所在文件夹，然后输入命令 katago.exe contribute -config contribute_example.cfg 即可开始跑普啦！  
colab跑普：[跑普链接](https://colab.research.google.com/drive/1cxg1m2Dx-jReCGrMAAoE9mpCmlfBINTy?usp=sharing#scrollTo=cr_mVMzXi4KM)，修改用户名密码后运行即可。# ikatago-faq

## 有什么软件可以运行katago/ikatago呢？

### 电脑：

lizzle yzy,可到官方QQ群下载，群号867298807  
