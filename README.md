# GITTRAINING

仅用于熟悉git操作

🈲严禁传🐎，病毒啥的

使用请先fork，尽量不要给主仓传东西

常用git操作只展示操作步骤如需彻底了解git请移步菜鸟教程https://www.runoob.com/git/git-tutorial.html

里面git命令含义自行百度或者等日后更新吧

## 常用git操作

1.fork

仓库页面右上角
![image](https://user-images.githubusercontent.com/105794142/180171208-e381aa95-39cb-46a3-8aff-edc179ba1373.png)


2.如何拉取仓库到本地

找个位置打开cmd`git clone +仓库的链接（右边绿色的code点开，像gittraining就是https://github.com/heyaspirin/gittraining.git）`
![image](https://user-images.githubusercontent.com/105794142/180171401-100424bb-6a82-433c-923d-d1d037baa247.png)


3.如何在本地添加过文件后上传

在本地仓库目录下打开命令行`git add .`接着`git commit -m "注释（想些啥写啥上传后会显示的）"`最后git push

4.如何保持自己的仓库代码同步
当自己的仓库里有更改的时候在本地仓库目录下`git pull`就会把更新的部分拉到本地啦
如果之前以及pull过但你在本地删除了某个文件，这时候如果`git pull`会默认没有修改这时候你想恢复的话呢就`git add .`然后`git reset --hard`就行了

5.如何与主仓保持同步
敬请期待
