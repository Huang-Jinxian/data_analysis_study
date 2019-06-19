# Day0 Study

## 任务
* 学习使用git上传文件至Github
* Jupyter notebook环境搭建

### Git使用
1. 创建本次学习使用的仓库`git@github.com:Huang-Jinxian/data_analysis_study.git`  
2. 使用`.gitignore`文件忽略不用跟踪的文件

### 搭建Jupyter notebook环境
1. 已经安装了python3.6，因此只需要安装jupyter就好了，使用`pip3 install jupyter`进行安装  
2. 在当前git项目路径下执行`jupyter notebook`开启了notebook客户端，自动打开notebook网页  
3. 按照书中的提示，创建了一个notebook，执行python命令，正确执行没有问题

> 在新建的notebook中执行命令时，我发现文件夹里面自动生成了一个隐藏文件夹`.ipynb_checkpoints`  
里面的文件就是新建的notebook，只不过名称多了`-chheckpoint`  
所以这个文件夹的作用是什么？notebook执行时的缓存文件吗？