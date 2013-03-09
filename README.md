本地建立一个Git版本库。
$ mkdir helloworld
$ cd helloworld
$ git init
然后在版本库中添加示例文件，如README.md文件，内容同前。
$ git add README.md
$ git commit -m "README for this project."
为版本库添加名为origin的远程版本库。
$ git remote add origin git@github.com:gotgithub/helloworld.git
执行推送命令，完成GitHub版本库的初始化。注意命令行中的-u参数，在推送成功后自动建立本地分支与远程版本库分支的追踪。
$ git push -u origin master
