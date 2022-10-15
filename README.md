# bme.github.io

第一步：新建仓库

在GitHub上，创建一个新的仓库，仓库名设置为如下格式：账户名.github.io

第二步：添加文件

创建后，这里为了简化操作，直接选择创建文件：

接下来输入文件名：index.html，并在里面写一点内容：比如一句话。


然后拉到下面直接提交即可：

当然你也可以用git方法来实现：

git clone https://github.com/username/username.github.io

cd username.github.io

echo "官方文档 https://pages.github.com/" > index.html

git add --all

git commit -m "Initial commit"

git push -u origin main

第三步：等待

等待 1 到 5 分钟，在浏览器输入 账户名.github.io，比如我的网址就是https://pangyiming.github.io/，应该就可以显示了。

附上官网教程链接 ：https://pages.github.com/

来自https://blog.csdn.net/u013814964/article/details/125666616 
