


八一效率工具推荐（qq:19259128696）：

1. notepad++ 文本编辑器
2. VSCode  前端编辑器/文本编辑器
3. f.lux 护眼工具
4. 火萤酱 快速搜索工具，功能自己摸索吧。 打开快捷键：CTrl+Q  自定义设置
5. mathpix  截图latex公式转化 
6. screenshot 截图文字转化或同声翻译
7. Snipaste 一个简单但强大的贴图工具，同时也可以执行截屏、标注等功能。 打开快捷键：F1 

8. PicGo 呢？—— 图床客户端。

9. 幕布—— 文档管理+思维导图。


这是如何设置软件开机自启。

好了，我暂时就推荐这么几个工具给大家。回到 Git 教学。

-----------------------------------------------------


使用 Git 和 GitHub 步骤：

提前推荐个软件，你在用的：Typora。

  1. 先配置 SSH（一个协议）。请看演示
	1. 电脑 Git Bash： ssh-keygen -t rsa  过程中，回车即可。
	2. 打开github--> setting --> SSH,添加 SSH  public 文件内容。
	测试下：ssh git@github.com 看到：You've successfully authenticated 表示成功。
  2. 可以使用 Git 命令玩了。 就是这么简单。经常用的命令就是如下几个：
	1. git status 查看本地仓库状态
	2. git add .   添加所有改动到暂缓区，git add a.txt 这是添加a.txt单个文件
	3. git commit -m "你的注释说明"
	4. git push 提交到GitHub
	

如何使用 Git 提交自己的文件到 GitHub？

	1. 选择仓库的 ssh 的地址
	2. 克隆(下载),比如：git clone git@github.com:mathflow/LaTex_Notes.git
		可以看到克隆下来后有个 .git 后缀隐藏文件，即为记录本地仓库的一切改动。
	3. 切换到仓库目录
	4. 修改
	5. git add .
	6. git commit - m "注释说明"
	7. git push 提交到远程服务器GitHub
	注：随时可以使用 git status 查看仓库状态。另外，git branch -a 查看和
		远程服务器关联情况。
		
	这个期间应该会要求你配置下name和email的，你这里肯定是你之前已经配置过了。
END！
?	
GitHub 挺多资料的，好好利用!

----------------------------------------------------------------------

如何使用 GitHub 作为图床？

1. Github上新建一个仓库，作为存储图片的。（仓库私有、公有，随你吧）
2. 新建 token，比如这是你的：8692ec2d94698d7cc14408257ee5bf4e***..
2. 在PicGo配置下即可。其中的，分支名设置为默认的：master即可

注1：我帮你设置的上传快捷键为 Ctrl+W(被占用了，你自己重新设置为自想要的吧)
注2：还是设置仓库为公有仓库吧，避免出现莫名其妙问题！
注3：上传成功之后，默认粘贴板的地址为这样的：![](https://raw.githubusercontent.com/mathflow/ImagesBed/master/images/20190202224740.jpg)

注4：如果要上传到仓库的文件夹 /images 下，在存储路径处设置为：/images。

注5：自定义域名不设置也行。
?	（但如果出问题，那就设置为这样的：
https://github.com/mathflow/ImagesBed/blob/master，但前提是你的仓库是公开仓库）

注6：建议还是设置为时间戳重命名把，这样文件名称就为时间戳形式。

注7：使用github做图床，速度上你懂得，有点慢。每个仓库有1000g存储容量。

This team is mainly used for template making in universities. Welcome to LaTeX users!


TeX-degree-template-making





更新时间2019年4月12日