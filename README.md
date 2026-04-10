# test_git_command

git命令学习：https://www.runoob.com/git/git-basic-operations.html

1.学习如何创建分支、查看与clone分支的区别、查看改动了哪些文件、创建新分支提交到本地再切换分支拉取新的

```bash
  104  git status
  105  git add .
  106  git commit -m "debug "
  107  git config --global user.email "zekun.guo@zelostech.com"
  108  git config --global user.name "zekun.guo"
  109  git commit -m "debug"
  110  git branch
  111  git checkout -b debug
  112  ls
  113  git status
  114  git branch
  115  git checkout master
  116  git reset HEAD~1
  117  git chekout .
  118  git checkout .
  119  git status
  120  rm -rf model_full_structure.txt 
  121  git status
  122  git log
  123  git checkout debug
  124  git log
  125  git checkout master
  126  git checkout -b debug2
  127  git log

```
