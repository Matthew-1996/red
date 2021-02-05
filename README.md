# red
**在这里，首先，我们记录下vs code链接github的步骤**  
github链接vs code  
借助git，连接双方  
1、https://git-scm.com/download/mac  
git官网  
2、安装homebrew  
https://brew.sh/index_zh-cn  
3、安装git  
4、配置环境变量，没装过可能不用？  
https://www.cnblogs.com/s-qiu/p/7019391.html
5、https://www.jianshu.com/p/6de75cba5c8a  
其中，cat ~/.ssh/id_rsa.pub，这一步是有问题的。我发现可能每个人的文件名不一样，需要根据上一步生成的内容修改。  

最后需要采用的操作流程是：  
1、从github克隆，保存在本地  
2、修改本地文件，保存  
3、将修改分支，**提交**到git
4、！！！还要再推送到github