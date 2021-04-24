# ikatago FAQ

## 都有什么租机平台呢？

### 以下是暂时已知的租机平台，皆可将ikatago.ipynbs上传到juypter notebook使用：

-[智星云](http://www.ai-galaxy.cn/)，直接在手机小程序选择ikatago镜像，输入用户名和密码后即可运行。  
-[恒源智享云](https://gpushare.com/)，可选择在juypter内上传，或使用ikatago镜像，[教程](https://gpushare.com/docs/best_practices/ikatago/)在此。  
-[极链云](https://cloud.videojj.com/)  
-[mistgpu](https://mistgpu.com/)  
-[Featurize](https://featurize.cn/)  
-[矩池云](https://www.matpool.com/)  
-[极客云](https://www.jikecloud.net/)  

### 以下是可上传文件的云电脑平台，可将群文件中的ikatago-server整合包上传到云桌面使用：

-[顺网云电脑](https://cpc.icloud.cn/)  
-[青椒云电脑](https://www.qingjiaocloud.com/)

## 权重类问题

### katago最强最新的40b权重可以在那里下载呢？

最新最强的权重可以在[katago分布式训练官网](https://katagotraining.org/)下载，找到Strongest confidently-rated network字样，后面便是下载链接。  
例：Strongest confidently-rated network: [kata1-b40c256-s7660552704-d1858058038](https://media.katagotraining.org/uploaded/networks/models/kata1/kata1-b40c256-s7660552704-d1858058038.bin.gz)

### katago目前最强的60b权重在哪里下载呢？

[60b248号权重](https://media.katagotraining.org/uploaded/networks/models/kata1-extra/b60c320-s2480283136-d1813743898.bin.gz)

### 听说有混血权重？

是的，DreamKeeper大大写了一个colab混血工具，混的好的话有可能超越官权。[链接](https://colab.research.google.com/drive/116DUPlzw6JQvB4-kqrbvk0ad50-QcSJL#scrollTo=nPaa2KJt8Kyn)在此

### 我有可能帮助到katago训练吗？

当然可以！我们很鼓励大家贡献自己的算力使katago更为强大！
事先准备：在[官网](https://katagotraining.org/)注册一个账号，记得验证邮箱哦！  
如果是使用本机：在contribute_example.cfg修改用户名密码和想要同时跑的盘数，在命令行cd到katago所在文件夹，然后输入命令 katago.exe contribute -config contribute_example.cfg 即可开始跑谱啦！  
colab跑普：[跑谱链接](https://colab.research.google.com/drive/1cxg1m2Dx-jReCGrMAAoE9mpCmlfBINTy?usp=sharing#scrollTo=cr_mVMzXi4KM)，修改用户名密码后运行即可。

## 有什么软件可以运行katago/ikatago呢？

### 电脑：

-lizzie yzy，受到广泛使用，可到官方QQ群下载，群号867298807。  
-[lizzie](https://github.com/featurecat/lizzie)，lizzieyzy便是源自此软件。  
-[sabaki](https://github.com/SabakiHQ/Sabaki)，这个软件的优点是外形美观,但需少量计算机知识。  
-[goreviewpartner](https://github.com/pnprog/goreviewpartner)，集成了几种AI。  
-[KaTrain](https://github.com/sanderland/katrain)，这个软件整合了很多katago引擎，很方便。  
-[LizGoban](https://github.com/kaorahi/lizgoban)  
-[q5Go](https://github.com/bernds/q5Go)  
-[gogui](https://github.com/Remi-Coulom/gogui) 

### 手机：

安卓：  
-badukAI，有加速权重，能提升katago和leelazero在手机上的运行速度，可在ikatago群文件内下载。   
-阿Q围棋，分为专业版（付费）和免费版，专业版可使用ikatago。进群获取，普通版：278743263，专业版：772521774  
  
苹果ios：  
-[围棋老师](https://apps.apple.com/us/app/%E5%9B%B4%E6%A3%8B%E8%80%81%E5%B8%88/id1442035374?l=zh)，付费软件，有对苹果手机处理器的加速。  
-[围棋ai--katago围棋老师，付费软件](https://apps.apple.com/cn/app/%E5%9B%B4%E6%A3%8Bkatago-%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E5%9B%B4%E6%A3%8B%E8%80%81%E5%B8%88/id1509047602)，可以使用ikatago及作者提供之机器，但如不购买VIP,机器速度极慢。

## 我出门在外，想用手机连接自己的电脑分析棋，怎么办呢？

可以到ikatago群文件下载ikatago-server整合包，下载后解压，看使用说明，内有指示。

## 最新版的ikatago client是github上的1.3.1版吗？

不是，可以到ikatago群文件内下载最新的1.3.3，但没什么大改动，1.3.1可继续使用。

## KataGo的最新引擎可以在哪里下载呢？

[KataGo 1.8.2 下载链接](https://github.com/lightvector/KataGo/releases/tag/v1.8.2)

## ikatago是一个互惠互助的社群，有什么问题可以在群内向群主及管理员提出哦！
