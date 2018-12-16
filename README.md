##### linux开发vm虚拟机开发环境共享

有比较长的时间没有分享了，最近抽出来点时间整理一个工具，这个工具主要是针对于golang，php，java开发者的linux环境，当然可能java程序员一般都是用界面工具开发，这里就不详细纠结了，但是golang或者php开发者，对linux开发虚拟机还是比较需要的，因为线上的环境基本都是linux系统服务器。需要一个和线上差不多的环境。我相信大部分开发者都喜欢在windows上面安装vm，然后按照vm虚拟机系统。然后用虚拟机开发。用mac的一般都是直接在mac上面装，这类用户就不说了。

这里我们来说一下使用我的这个虚拟机的教程：

1.装一下vmvare workstation 

2.装完了之后点击file->open 找到刚才下载的zengzhihai.7z压缩之后的文件路径，进行打开。然后就可以启动了。

链接：https://pan.baidu.com/s/1YNXVxO-Av-nb-QnnrDuIzQ 

提取码：frov 



vmware workstation 安装教程：https://jingyan.baidu.com/article/9f7e7ec09da5906f281554d6.html

此虚拟机安装了go，java，nginx，mongo，mysql，redis，memcached。涉及到一些程序的start脚本都在/root/start.sh下面。

所有的程序安装目录都在/use/local/ 下面

所有的软件的下载路径都在/root/soft下面

如果涉及到php的一些安装扩展，可以在此路径下面找到。



好了 我大概介绍这么多吧，谁需要的话直接拿走。免得每次都换个电脑或者换个系统都需要重装，比较麻烦。有问题大家可以提问。









