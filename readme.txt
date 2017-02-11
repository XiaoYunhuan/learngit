1.cd 进入目录
2.git init 把当前目录变成git可以管理的仓库
3.添加文件：a.单个文件: git add readme.txt
            b.全部文件: git add -A
4.提交修改： git commit -m"一定要写备注"
5.查看是否还有未提交：git status
6.查看最近日志：git log
7.版本回退操作：
a.回退一个：git reset -hard HEAD^
b.回退二个：git reset -hard HEAD^^
c.回退多个：git reset -hard HEAD~100
8.(第一次链接)远程仓库的提交: git remote add origin git@github.com:XiaoYunhuan/learngit.git
  仓库关联：git push -u origin master
9.(第二次以后)远程仓库的提交：git push