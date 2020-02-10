# github学习报告  
`@Author 蒋璐璇`  
`@Date 20190209`  
[github有关概念](#1) | [git](#2) | [github](#3)| [开源项目贡献流程](#4)

emmm我也不知道以后我会不会真香，反正我现在觉得它一点都不香。我看到满屏的英文就脑壳痛【来自英语学渣的哭泣】

# <a id='1'>github有关概念</a>

**github**  一个开源社区（托管项目代码）
![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/1.PNG "图片Title")


![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/2.PNG "图片Title")


![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/3.PNG "图片Title")


**git** 一个管理代码的工具

        两种模式（bash命令行模式、cui图文模式）
        
        三个工作区域（仓库、暂存区、工作区）
        
        在工作区进行编辑文件后缓存到暂存区后统一上传到仓库
![概念示意图](https://raw.githubusercontent.com/LuxuanJiang/github-/master/4.PNG "图片Title")

**Repository** 仓库，存放项目代码

**Fork**  复制克隆项目

**Pull Request** 发起请求，用于合作、改进项目

[回到顶部](#readme)

# <a id='2'>git</a>

**git初始化及仓库创建和操作【本地仓库】**

1、设置用户名和邮箱
```
git config --global user.name 'username'
git config --global user.email 'eamail'
```

2、创建文件夹
```
mkdir filename //新建文件夹
```
3、在文件内初始化git（把文件变成仓库）
```

cd filenanme //进入文件夹
git init  //初始化
```
注：初始化后，git文件夹为隐藏文件
4、向仓库添加文件
```
touch filename //新建文件
git add filename //将文件上传到暂存区
git commit -m '描述' //添加描述
git push //将暂存区的文件统一上传仓库
```

5、修改删除文件
```
vi filename //编辑文件
：wq //保存退出文件
cat filename //显示文件内容
git rm filename //从git中删除文件
git comimt -m '描述' 
```

**git远程仓库（备份共享）**
```
git clone 仓库地址
//重复上述步骤
git push
```

**个人站点**

1、新建仓库（仓库名必须为用户名.github.io)

2、在仓库内新建index.html的文件
 
3、个人站点的地址为https：//用户名.github.io

注：仅支持静态网页

[回到顶部](#readme)

# <a id='3'>github</a>
1、创建仓库

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/5.PNG "图片Title")

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/6.PNG "图片Title")

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/7.PNG "图片Title")

2、创建新文件

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/8.PNG "图片Title")

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/9.PNG "图片Title")

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/10.PNG "图片Title")

3、留言

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/11.PNG "图片Title")

![](https://raw.githubusercontent.com/LuxuanJiang/github-/master/12.PNG "图片Title")

[回到顶部](#readme)

# <a id='4'>开源项目贡献流程</a>

1、新建lssue

        提交建议或想法
        
        
2、pull request

        fork项目
        
        修改自己仓库的项目
        
        新建pull request
        
        等待作者审核
        
[回到顶部](#readme)
