#my_math_note

管理 git 项目的方法：

1. 网页上新建项目，复制地址，在电脑上打开所要放这个文件的位置
	git clone 右击粘贴网址 // 克隆项目

2. git 上传文件方法：
	git add -A .  // 将文件夹中的所有改动添加到缓存区
	git commit -m "some note"  // 将缓存区中的所有文件提交到本地仓库，注意：some note 是一句话
	git push origin master  // 将本地仓库推送到云端

3. git 下拉文件的方法：
	git pull

4. 安装上传工具：
	打开cmd：ezgit

关于文件结构的说明：

1. 由于使用了 subfiles 宏包，每个文件都可以单独编译。其中 math_note.tex 文件是主文件。

2. SIAE_logo 文件是我们学院的院训，我将其制作成pdf文件在制作笔记本封面的时候使用。

3. figure 与 image 文件夹是存放插图的文件夹。
