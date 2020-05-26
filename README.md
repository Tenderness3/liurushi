github  使用手册


star 收藏
fork 复制仓库
pull request 请求更新仓库repository
watch  关注
issue  发现代码bug 需要讨论

首先创建一个文件touch a2.php
然后添加到暂存区  git add a2.php
可以查看暂存区的东西  git status
最后提交到仓库 git commit -m 'add a2.php'
查看暂存区没有东西  git status


vi a1.php    进入vi编辑
cat a1.php   查看文件

三部删除操作
rm -rf a1.php      删除a1.php
git rm a1.php
git commit -m '第一次通过git删除文件'



git clone 仓库地址下载


怎样将本地文件上传到git库
首先创建文件touch 22.php
然后添加到缓存区 git add 22.php
其次提交记录  git commit -m '第几次提交到git'
最后git push  等待完成
