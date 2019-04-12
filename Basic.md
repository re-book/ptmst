  ![](https://img.shields.io/badge/Language-TeX-yellow.svg)![](https://img.shields.io/badge/version-0.1-red.svg)![](https://img.shields.io/github/last-commit/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/repo-size/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/languages/code-size/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/followers/hoganbin.svg?label=Follow)

# Hoganbin_LaTeX_Template

这是本人制作的本科学位毕业设计LaTeX模板，欢迎star!



###八一效率工具推荐（qq:19259128696）

1. notepad++ 文本编辑器
2. VSCode  前端编辑器/文本编辑器
3. f.lux 护眼工具
4. 火萤酱 快速搜索工具，功能自己摸索吧。 打开快捷键：CTrl+Q  自定义设置
5. mathpix  截图latex公式转化 
6. screenshot 截图文字转化或同声翻译
7. Snipaste 一个简单但强大的贴图工具，同时也可以执行截屏、标注等功能。 打开快捷键：F1 
8. PicGo 呢？—— 图床客户端。
9. 幕布—— 文档管理+思维导图。

- 关于如何设置软件开机自启。把你需要开机自启的软件.exe创建快捷方式，然后剪切在命令行输shell:startup复制到该文件夹中，最后你在命令行输入msconfig就会发现在你的启动程序项目就有你设置的软件。

好了，我暂时就推荐这么几个工具给大家。回到 Git 教学。

------

###认识Git 与 GitHub

- Git是一款免费、开源的分布式版本控制系统Github是用Git做版本控制的代码托管平台
- Github是一个用Git做版本控制的项目托管平台。

GitHub就是一个免费托管开源代码的远程仓库。但是对于某些视源代码如生命的商业公司来说，既不想公开源代码，又舍不得给GitHub交保护费，那就只能自己搭建一台Git服务器作为私有仓库使用。

____________

### 开始安装Git

打开Git的官方网站，下载下来之后安装时选择默认选项即可

安装完成之后，在任意位置点击鼠标右键，菜单栏里看到**Git Bash**代表安装完成

安装完成后，还需要最后一步设置，在命令行输入：

**$ git config --global user.name"Your Name"**

**$ git config --global user.email"email@example.com"**

注意 git config 命令的 --global 参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。

___

###使用 Git 和 GitHub 步骤：

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

```
1. 选择仓库的 ssh 的地址
2. 克隆(下载),比如：git clone git@github.com:mathflow/LaTex_Notes.git可以看到克隆下来后有个.git 后缀隐藏文件，即为记录本地仓库的一切改动。
3. 切换到仓库目录
4. 修改
5. git add .
6. git commit - m "注释说明"
7. git push 提交到远程服务器GitHub
注：随时可以使用 git status 查看仓库状态。另外，git branch -a 查看和
	远程服务器关联情况。
这个期间应该会要求你配置下name和email的，你这里肯定是你之前已经配置过了。
```

END！
?	
GitHub 挺多资料的，好好利用!

------

如何使用 GitHub 作为图床？

1. Github上新建一个仓库，作为存储图片的。（仓库私有、公有，随你吧）
2. 新建 token，比如这是你的：8692ec2d94698d7cc14408257ee5bf4e***..
3. 在PicGo配置下即可。其中的，分支名设置为默认的：master即可

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