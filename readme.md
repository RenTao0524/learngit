@[TOC] git用法

### 初始化本地仓库

```bash
mkdir learngit
cd learngit
git init
```

### 工作区和暂存区(stage)

### [git远程仓库](https://www.liaoxuefeng.com/wiki/896043488029600/896954117292416)

### git常用指令用法

|指令|说明|
|---|---|
|git add file||
|git add .||
|git status||
|git diff file||
|git commit -m 'xx'||
|git log|查看提交详细日志|
|git reflog|记录每一次命令|
|git log --pretty=oneline|查看简化提交日志|
|git reset --hard HEAD^|返回上一次提交记录|
|git reset --hard commitid|返回指定提交记录|
|git checkout -- readme.txt|丢弃掉工作区的修改|
|git reset HEAD readme.txt|把暂存区的修改撤销掉|
|git log --graph|查看分支合并情况|
|git stash|暂存|
|git remote|远程分支|
