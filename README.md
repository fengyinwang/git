git
===

1、git基本命令
2、git init 将当前目录创建为版本库，实际上就是在当前目录里面创建了一个.git文件夹；
3、git clone【url】将服务器端的版本库clone一个到本地来，会在当前文件夹下创建一个项目文件夹，项目文件夹中有.git文件夹；
4、git config --global user.email xxx
   git config --global user.name xxx
  以上两个命令用来设置当前机器使用git的用户信息；
5、git log 可以查看当前版本库的日志信息，在没有.git文件夹的文件夹中无效；
6、使用.gitIgnore来忽略一些不想提交的文件；
7、使用git add【file】来把文件纳入版本库中，此时文件还没有提交到版本库；
8、git commit -m "this is a message"来进行提交，git的提交是本地操作的，可以说所有的操作都是本地的；
9、git satus 来查看版本库的状态，随时都可以使用，在没有.git文件夹的文件中无效；
10、git push origin master将本地版本库的信息推送到服务器端；
11、git pull 将服务器端的版本库信息同步到本地；
