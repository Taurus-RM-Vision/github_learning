# GitHub+Vscode代码管理教程
预备知识：
1. 安装GitHub Desktop并学习基础clone和push代码
   <p>视频教程： <a href="https://www.bilibili.com/video/BV13W411U7HY/?share_source=weixin_web&share_times=1&vd_source=b91afc82e63b14bfbf720e51d03b61b0" title="欢迎访问逐浪软件官网">【教程】使用GitHub Desktop管理你的项目</a>.</p>
    <p>文档教程： <a href="https://docs.qq.com/pdf/DZE15UXJVVkxzRlF2" title="欢迎访问逐浪软件官网">群文档汇总中【内部】github-desktop使用说明</a>.</p>
2. 安装vscode并安装插件Git Graph

本教程将会讲解github的一些基础概念、版本回退、创建与合并分支、代码冲突解决、以及在多人项目管理中的要求
作业：在本仓库中完成上述功能

## 1.git重要基础概念
* clone   将代码从云端下载到本地
* stash   暂存更改，可选择暂存某些更改进行提交（GitHub Desktop没有这个概念，只有changes,可以通过取消勾选不提交改更改）
![图片](resources\img_changes.jpg)
* commit    提交更改，commit之后以后就可通过回溯回到改版本，可以添加说明（说明最好讲清楚做了哪些更改，方便自己以后看，也方便别人）
![图片](resources\img_commit.png)
* push  将本地内容推送到远程仓库，推送之后别人才能通过pull或者进去GitHub网站看到你的更改
* pull  拉取代码，将云端代码更新到本地（通常需要解决冲突）
* branch    分支，在多人管理中创建不同分支同时工作，在进行merge进行合并
* merge     分支合并，字面意思（通常需要解决冲突）

## 2.vscode中Git Graph插件
这个插件可以可视化仓库各分支间的关系，非常有用
先下载该插件![图片](resources\img_gitgraph.png)
节点图打开方式，两种方法，建议直接底部打开
![图片](resources\img_gitgraph2.jpg)
节点图如下图所示，不同颜色代表不同分支
下图中双击写错了，单击就可以了
![图片](resources\img_gitgraph3.jpg)
点击查看某个commit的信息
![图片](resources\img_gitgraph4.jpg)

## 2.代码版本回退
注意：进行代码回退前先把当前代码commit一次
按以下步骤操作，界面右边是对应这次commit所作的更改，左边是他的更改前代码，右边是更改后的
![图片](resources\img_revert1.jpg)
点击恢复变化后会出现报错，不要害怕，这是因为回退的代码和你当前代码有冲突需要解决，弹窗直接close后打开vscode

change2
111
## 3.创建与合并分支

## 4.多人项目管理

