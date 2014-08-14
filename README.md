clonegit
========

创建远程仓库，本地克隆远程仓库
##以github为例，创建远程仓库clonegit##

![第一步](https://github.com/FEsy/clonegit/blob/master/img/step1.png)

##远程仓库创建成功##

![第二步](https://github.com/FEsy/clonegit/blob/master/img/step2.png)

##克隆远程仓库到本地仓库##

![第三步](https://github.com/FEsy/clonegit/blob/master/img/step3.png)

注意：	
你也许还注意到，GitHub给出的地址不止一个，还可以用	
	`$ git clone https://github.com/githubname/repname.git`	
实际上，Git支持多种协议，默认的
	`$ git clone git@github.com:githubname/repname.git`	

仔细阅读会发现我的clone地址可能不一样，是因为我本地配置了使用多个github账号，具体可参考[多个github账号的ssh keys 支持][1]

使用https除了速度慢以外，还有个最大的麻烦是每次推送都必须输入口令，
但是在某些只开放http端口的公司内部就无法使用ssh协议而只能用https。

[1]: https://github.com/FEsy/github