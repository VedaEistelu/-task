杭州电子科技大学
 大 作 业 报 告


课程名称      C++面向对象程序设计       
实验名称             大作业              
指导教师              吴敏               


学生姓名               沈佳斌               
学生学号              18062030              
学生班级              18063111              
学生专业           智能科学与技术           
实验日期              2019.12.19             

 
一、作业要求
熟悉Github的使用，采用nebula项目选择程序段或者自己编写单元测试进行运行，然后尝试寻找项目内问题进行Pr的提交。
二、结果报告
代码片段的运行

选择了对time文件夹中test目录内的DurationTest.cpp文件进行了更改，然后尝试编译，编译通过。
 ![make](https://github.com/VedaEistelu/-task/blob/master/pic/%E7%BB%88%E6%9E%81%E7%BC%96%E8%AF%91.png?raw=true)

之后运行该项测试，终端返回的结果显示运行成功，成功使该文件由休眠了11020ms到休眠6028ms
 ![run](https://github.com/VedaEistelu/-task/blob/master/pic/%E8%BF%90%E8%A1%8C.jpg?raw=true)
 ![run2](https://github.com/VedaEistelu/-task/blob/master/pic/%E8%BF%90%E8%A1%8C2.png?raw=true)

最后尝试提交了一个Pull Request到nebula项目上以让老师进行验收，git log显示VedaEistelu用户进行了3个commit
![status](https://github.com/VedaEistelu/-task/blob/master/pic/git%20status.png?raw=true)
![commit](https://github.com/VedaEistelu/-task/blob/master/pic/git%20commit.png?raw=true)
![log](https://github.com/VedaEistelu/-task/blob/master/pic/git%20log.png?raw=true)
![pr](https://github.com/VedaEistelu/-task/blob/master/pic/2019-12-23%2017-34-04%20%E7%9A%84%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE.png?raw=true)
![pr2](https://github.com/VedaEistelu/-task/blob/master/pic/2019-12-24%2017-30-59%20%E7%9A%84%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE.png?raw=true)
![pr3](https://github.com/VedaEistelu/-task/blob/master/pic/2019-12-24%2017-31-05%20%E7%9A%84%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE.png?raw=true)
三、问题解决
1.遇到的问题
1）在使用git clone操作进行nebula项目的拉取时，由于服务器与网络的相关问题，clone速度极慢，因此查询解决办法后，首先尝试更新本机中linux系统下对github的IP拉取地址，但发现速度仍然提不上去。之后尝试将nebula项目先转存到码云gitee上，再进行拉取，发现速度正常，成功clone项目。之后发现该项目在重启后拉取内容消失，无奈重复了两次终于不再出现该问题。

2）在进行Github的使用学习中，发现终端无法进行git push 来进行PR的提交，于是在老师的操作下绑定了ssh key，成功提交了PR

3）在nebula环境中进行操作时不知道如何具体进行，随后研究老师给出的指令集，进行模拟，理解命令的含义，最后成功运行。

四、实验心得
    本次作业，我熟悉了github的使用，之前只是在github上下载别人的成果，这门课程使我真正的参与到了github这个社区当中。初次在老师示例项目中提交了一个Pull Request。
在linux上创建了nebula的环境，尝试了cpp文件的编译和运行，知道了之后c++项目具体的运行环境与测试等。
在环境装配方面，明白了要锲而不舍，遇到问题就向有经验的人参考、请教，学习老师的操作，千万不能放弃，否则只会停滞不前。
