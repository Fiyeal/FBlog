## 安装MinGW-W64出现Error Res问题的解决方法
最近为了能在vscode中使用GCC，就按照[官方doc](https://code.visualstudio.com/docs/cpp/config-mingw)进行配置，其中就需要安装MinGW-W64，但是安装时总会出现Error Res的提示，如下

![image-20201125130836709](https://raw.githubusercontent.com/Fiyeal/image/main/sourceforge.png)

下面是解决方法！！

步骤：

1.首先我们需要到[SOURCEFORGE](https://sourceforge.net/projects/mingw-w64/files/)（官方把程序放在了这）里下载我们需要的压缩包，这里我就直接下载的x86_64-posix-seh（按需）（浏览器下载很慢的话可以试试迅雷）

![image-20201125131114747](https://raw.githubusercontent.com/Fiyeal/image/main/Error-res.png)

2.下载完成后就直接解压到某个路径就能直接使用了

配置环境变量的话就直接使用bin文件夹的路径。

