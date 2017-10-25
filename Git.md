# Git

[]: https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374027586935cf69c53637d8458c9aec27dd546a6cd6000	"学习地址"

## 1

```c
git init//初始化一个项目
git add //后面可以跟多个文件
git commit -m "xxx"//提交和注释
```

## 2

```c
git status//当前状态
git diff//查看不同
```

## 3

```c
git log//操作日志
git log --pretty=oneline//每项一行
HEAD 当前版本 上一个版本就是HEAD^，上上一个版本就是HEAD^^ HEAD~100//简写
git reset --hard HEAD^//回退版本
git reset --hard 3628164//回退到指定版本
```

## 4

```
git checkout -- file//撤销修改
git rm file//删除
```

## 5

```c
git remote add origin git@github.com:songsongtao/learngit.git//管理远程仓库
git push -u origin master//第一次提交push
git push origin master//正常提交
```

## 6

```c
git clone git@github.com:songsongtao/learngit.git//克隆仓库
```

