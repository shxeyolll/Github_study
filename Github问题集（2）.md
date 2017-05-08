# Github问题集（2）
5/8/2017 9:16:57 AM 
1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
创建新仓库 导入仓库 创建代码片段 创建组织
2. 如何能将仓库中的html文件直接解析成页面？   
打开一个仓库的settings找到github pages 选择 master branch
3. 如何删除仓库  
打开一个仓库的settings找到github pages 选择delete this repository 输入名字即可删除
4. Bash是什么操作系统的命令  
Linux
5. Pwd是什么命令  
查看当前工作目录的完整路径
6. Cd是什么命令  
改变当前目录 git --创建
7. Echo是什么命令  
用命令echo输出
8. 配置git用户名的命令  
git config --global user.name "yourname"
9. 配置邮箱的命令  
git config --global user.email "youremail@email.com"
10. 命令行换行方式  
\
11. 命令行终结方式  
Ctrl+c
12. 使用命令行比GUI方式有何优势  
文件管理，列出文件属性，使用crontab调度作业，安装软件包
13. 提交到本地仓库时为什么有暂存区  
处理变动 仓库空间必须通过暂存区
14. 新建代码仓库的命令  
git init
15. git clone [url] 这个命令的作用是  
将服务器上的仓库克隆到本地
16. 添加指定文件到暂存区的命令  
git add [file1] [file2]

17. 删除工作区文件，并且将这次删除放入暂存区的命令  
git rm [file1] [file2]

18. 改名文件，并且将这个改名文件放入暂存区的命令  
git mv [file-origin] [file-renamed]
19. 提交暂存区到仓库的命令  
git commit -m [message]  
20. 直接从工作区提交到仓库的命令  
git commit -a -m [message]

21. 显示变更信息的命令  
git status
22. 查看历史信息的命令  
git log  git log --online
23. Commit的意义是  
提交到仓库
24. Pull的意义是  
远程仓库下拉倒本地
25. Push的意义是  
本地仓库推送到远程仓库
