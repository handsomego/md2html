# md2html
* 脚本中使用了[marked](https://github.com/markedjs/marked)命令
 
 * 前提是要安装nodejs (Windows确保不是Xp因为nodejs最低是win7起步，像win10，8，都行)
 * Windows用户直接安装Git软件，，或者安装Windows下的Linux子系统（具体在“应用商店”中，搜索“Ubuntu”）
#### 使用方法如下
```
./md2html 文件夹名 #比如说./md2html TestOne
```
原理就是把文件夹下的md文件，转换成md.html文件
还有就是会遇到转换成html格式后，里面的超文本链接如果是指定的是相对路径的话，文件会转换不对。
