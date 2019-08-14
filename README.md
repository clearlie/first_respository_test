# first_respository_test

这个文件用于测试学习GitHub与本地Git的连接

1、注册一个GitHub账号，点击左上角的new按钮，新建一个本地仓库。

2、打开Git bash，创建SSH key，输入ssh-keygen -t rsa -C "youremail@example.com",三次回车确认后打开id_rea.pub文件，
复制里面的公钥到GitHub里面的settings里的ssh keys.

这就简单的完成了远程库与本地库的连接。

下载与上传操作

1.打开Git bash，输入git clone 'github的文件地址（为ssh地址）'，即可完成下载。

2.在Git bash中，输入git push -u origin master（分支名）即可完成相关分支的文件上传。


