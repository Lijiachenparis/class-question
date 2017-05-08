# github问题集一
1. github是什么  
gitHub 是一个面向开源及私有软件项目的托管平台
2. git是什么  
git是一款免费、开源的分布式版本控制系统
3. 学习github的5个理由  
(1)项目开发中必须用到版本开发工具      (2)可以找到许多开源项目      (3)全球最大的托管平台，有许多的技术大神      (4)可以接触到许多前沿技术      (5)可以记录个人成长  
4. github的优势是什么  
（1）GitHub 只支持 Git 格式的版本库托管，比较简单； （2）GitHub 对 Git 版本库提供了完整的协议支持，支持 HTTP 智能协议、Git-daemon、SSH 协议（3）GitHub 提供在线编辑文件的功能，不熟悉 Git 的用户也可以直接通过浏览器修改版本库里的文件     （4）将社交网络引入项目托管平台是 GitHub 的创举，用户可以关注项目、关注其他用户进而了解项目和开发者动态     （5）特色的工作模式，项目的 Fork 和 Pull Request 构成 GitHub 最独具一格的工作模式。对提交代码的逐行评注及 Pull Request 构成 GitHub 特色的 代码审核 (6)GitHub 通过私有版本库托管、面向企业的版本库托管和项目管理平台、人员招聘等付费服务获得了商业上的成功，这种成功使得 GitHub 不必以页面中嵌 入广告的方式维持运营，最大的受益者还是用户 (7)GitHub 网站采用 Ruby on Rails 架构，在 Web 设计中运用了大量的 JavaScript、AJAX、HTML5 等技术，支持对使用 Markdown 等标记语言的内容进 行渲染和显示等。关注细节使得 GitHub 成为了项目托管领域的后起之秀。
  
5. 通过github年度报告让你记忆最深刻的信息有哪些  
世界上的各大公司在github上都有自己的开源项目，而且非常活跃。  
6. github上有可以个人账号 还可以有（ 组织 ）账号  
7. github上面的两个组成要素是什么  
组织或个人；仓库
8. github上两个重要页面  
个人主页和数字仪表板
9. 主页菜单都包含什么  
overview,repositories,stars,followers,following  
10. 仓库的心跳线代表什么  
仓库的活跃度
11. star的作用是？  
关注别人项目
12. fork的作用是？  
参与别人项目
13. watch的作用是？  
关注别人项目，项目作出更改时会收到信息
14. 搜索结果分别有哪些类别  
repositories,code,dommits,lssues,wikis,users
15. 你在github上挖到什么宝  
关注了我所学习的机器学习项目，关注了几个技术大牛

# github问题集二
1.	个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
(1)new repository:创建新的仓库     (2)import repository:导入仓库      (3)new gist：创建一个新的要点      (4)new organization：创建一个新组织
14.	如何能将仓库中的html文件直接解析成页面？  
在相应仓库下打开settings设置菜单找到GitHub pages，将Source下none改为master branch并保存即可。

15.	如何删除仓库  
在相应仓库下打开settings设置菜单找到GitHub pages，点击Danger Zone下的Delete this repository，输入要删除仓库名即可删除。
16.	Bash是什么操作系统的命令  
linux
17.	Pwd是什么命令  
显示当前工作目录
18.	Cd是什么命令  
更改工作目录
19.	Echo是什么命令
在显示器上显示一段命令
20.	配置git用户名的命令  
git config --global user.name "用户名"
21.	配置邮箱的命令  
git config --global user.email "邮箱名"
22.	命令行换行方式  
\
23.	命令行终结方式  
ctrl+c
24.	使用命令行比GUI方式有何优势  
命令行操作可以进行批处理
25.	提交到本地仓库时为什么有暂存区  
（1）原材料入库，未检验或检验后有疑惑，待处理。     （2）成品入库，未检验或检验后有疑惑，待处理。      （3）要领出的东西比较多，为了节约时间，提前做好准备，放在暂存区。      （4）入库的库位一时没准备好，暂时放一下。      （5）正常检查过程中发现有疑问的物品，暂时放一下。
26.	新建代码仓库的命令  
git init
27.	git clone [url] 这个命令的作用是  
克隆远程仓库
28.	添加指定文件到暂存区的命令  
git add
29.	删除工作区文件，并且将这次删除放入暂存区的命令  
rm
30.	改名文件，并且将这个改名文件放入暂存区的命令
git mv
31.	提交暂存区到仓库的命令  
git commit –m
32.	直接从工作区提交到仓库的命令  

33.	显示变更信息的命令  
git status
34.	查看历史信息的命令  
git log
35.	Commit的意义是  
提交
36.	Pull的意义是  
将远程仓库的提交拉下到本地
37.	Push的意义是  
将本地的提交推送到远程仓库

# MarkDown相关问题整理
1.	MarkDown是什么？  
是一种轻量级的标记语言  
它使我们专心码字，用标记语法，来代替常见的排版方法，可以使普通文本内容具有一定的格式
2.	MarkDown的特点？  
纯文本内容，兼容所有的文本编辑器与字处理软件；  
可以放到版本管理系统中，追踪历史变更；  
轻松的导出HTML,PDF和本身的.md文件；  
简介，高效，可读，直观，学习成本低；  
专注你的文字内容而不是排版样式，安心写做  
3.	MarkDown的用途？  
IT人士：写日志，技术文稿，记录代码片段，撰写文档；  
科研人员/学生：撰写科技论文，记笔记；  
求职者：制作求职简历；  
4.	MarkDown的编辑工具有哪些？  
Mac OS X:Mou;  
windows: MarkdownPad MarkPad;  
Linux:ReText;
Web:简书，github，有道云笔记.  
5.	MarkDown的区块元素和区段元素分别包含哪些？  
区块元素：  
段落和换行;标题;列表;代码区块;分割线;区块引用Blockquotes  
区段元素：  
链接;强调;代码;图片  
